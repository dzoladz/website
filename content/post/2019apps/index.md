+++
date = "2019-12-30T11:00:00"
draft = false
tags = ["applications"]
title = "Apps I'm Taking into 2020"
math = false
summary = "A short list of applications that I've found useful in 2019."

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
   preview_only = false
#  # Caption (optional)
#  caption = ""
#
#  # Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, #Bottom, BottomRight
   focal_point = "Center"

+++
While it's a major challenge to identify all of the scripts, command line tools, and web-based applications that have influenced my thoughts and workflow over the previous year,
here's a set of applications that I'm excited to take with me into the new year.

[Joplin](https://github.com/laurent22/joplin)  
Built upon node.js and electron, Joplin is an open source note taking application. At the moment, I'm using it as a well-structured notebook to recall quotes and collect ideas of all sorts. With the ability to sync notebooks to both [OwnCloud](https://owncloud.org/) and [NextCloud](https://nextcloud.com/) - as well as several other storage solutions - the availability of notebooks from divergent OSes and environments makes it an application that I'll enjoy on many occasions.

[Dockstation](https://dockstation.io/)  
If you want: (1) a gentle, graphical, introduction to engineering microservice-based applications with Docker Compose, (2) an interface to the container registry of Docker Hub, and (3) the ability to expose your container logs with the click of a button, DockStation is a wonderful gateway into the world of containers. I develop all of my `docker-compose.yml` files using Dockstation on macOS.

[Pi-Hole](https://pi-hole.net/)  
Running on a raspberry pi 3 on my home LAN, Pi-Hole provides DNS-level ad blocking on the network. I'm using Pi-hole to assign IP addresses to client on the LAN via DHCP services.  Via [dnsmasq](https://wiki.debian.org/dnsmasq), Pi-hole is also responsible for resolving a few host names on the LAN for applications like my Koha instance and backup server.

[Jekyll](https://jekyllrb.com/)  
While working on the Code4Lib web team for the 2020 annual conference, I've become acquainted with this ruby-based static site generator. I've been using [Hugo](https://gohugo.io/) for my personal website, as well as for the [Consortium of Ohio Libraries](http://info.cool-cat.org/) website, for roughly 2 years. Jekyll as several themes for project documentation and product marketing that have simple, yet complete, designs. I'll likely explore these themes for other projects in 2020.

[Bitwarden](https://bitwarden.com/)  
As I'm currently using LastPass, I've only begun to evaluate the full potential of BitWarden. I prefer open source applications, but this password management solution falls into the aspirational category for the coming year.

[GitLab](https://gitlab.com/)  
According to the project website, "GitLab is a complete DevOps platform". My main reason for creating a GitLab account is to explore a broader range of open source projects, whose primary source code repository lives within the GitLb ecosystem. As an example, the Evergreen ILS community writes documentation using [Asciidoc](http://asciidoc.org/). Experiments have begun using [Antora](https://antora.org/) for generating Evergreen documentation. Antora's source code resides on GitLab.
