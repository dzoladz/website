---
date: "2019-11-30T11:00:00"
draft: false
tags: ["applications"]
title: "Curses, It's Glances"
math: false
summary: "Python-based real-time system monitoring"

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
image:
   preview_only: false
#  # Caption (optional)
#  caption: ""
#
#  # Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, #Bottom, BottomRight
   focal_point: "Center"

---

There's definitely an argument to be made for using lightweight apps that minimize installed dependencies in an effort to: (1) minimize the surface area for vulnerabilities and attack vectors, and (2) reduce application complexity for  troubleshooting purposes when something inevitably goes wrong. However, there needs to be a balance between security gains and pleasure in using an application, what's the point in installing it in the first place if you aren't going to use it?

An application that sits in the sweet spot is [Glances](https://nicolargo.github.io/glances/).

Glances uses a plugin archiecture. The documentation contains a [current list of available plugins](https://glances.readthedocs.io/en/stable/aoa/index.html). One of the plugins that deserves highlighting is the AMP (Application Monitoring Process) plugin. AMPs are simple regex statements written into the Glances main `glances.conf` configuration file that allow the user to monitor any running processes. Glances configuration file is written in the human readable INI format.

### Installation

On macOS Catalina, I'm using Homebrew as my package manager.

```bash
brew install glances
```

That's it. Simple. But if you're like me, you'll want to adjust the default configuration. The glances directory does not exist by default, so you’ll also need to create it by doing:

```bash
mkdir /usr/local/etc/glances
```
and then,

```bash
cat /usr/local/Cellar/glances/3.1.3/share/doc/glances/glances.conf > /usr/local/etc/glances/glances.conf
```

## Keybindings (Interactive Commands)
A sampling of the in-app toggles that I've found useful.

<kbd>Shift</kbd>+<kbd>D</kbd> __show/hide Docker module__  
<kbd>Shift</kbd>+<kbd>A</kbd> __show/hide AMPs module__  
<kbd>&#8592;</kbd><kbd>&#8594;</kbd> __move through Tasks menus__  
<kbd>h</kbd> __show Help__  
<kbd>n</kbd> __show/hide Networks module__  
<kbd>1</kbd> __toggle global CPU and per-CPU stats__  
<kbd>2</kbd> __show/hide left sidebar__  
<kbd>5</kbd> __show/hide top menu__


## Follow up  

Of course, [ReadTheDocs](https://glances.readthedocs.io/en/stable/index.html).

Glances provides several export options for statistical data. One option is Elasticsearch. Indexing the usage data from macOS to be visualized in Kibana running on localhost is a likely next step.
