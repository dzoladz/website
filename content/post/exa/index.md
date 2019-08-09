
+++
date = "2019-08-09T11:00:00"
draft = false
tags = ["applications"]
title = "Why ls is exa"
math = false
summary = "tl;dr: informative metadata at a glance"

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

One of the most common commands that I execute in the terminal is simply to list the contents of a directory. Since I do this so often, being able to quickly and easily digest vast amounts of information about the content of the directory is essential. That's where [exa](https://the.exa.website/) shines.

Out-of-the-box, the default color scheme of `exa` is finely tuned. I found the intricate use of subtle color distinctions distracting, rather than informative. As such, I would need to modify the color definitions to suit my personal goals of: (1) being able to easily differentiate between directory content that my current user owns or is a member of the assigned group, (2) rapidly distinguish between files and directories, and (3) generally list common metadata elements that experiencing has shown to be frequently useful in troubleshooting an issue.

For the moment, here's what I'm using:

```bash
# ------------------------------
# exa - Color Scheme Definitions
# ------------------------------

export EXA_COLORS="\
da=38;5;245:\
di=38;5;14:\
sn=38;5;28:\
sb=38;5;28:\
uu=38;5;40:\
un=38;5;160:\
gu=38;5;40:\
gn=38:5:160:\
bl=38;5;220:\
ur=37:\
uw=37:\
ux=37:\
ue=37:\
gr=37:\
gw=37:\
gx=37:\
tr=37:\
tw=37:\
tx=37:\
su=37:\
sf=37:\
xa=37"
```

`exa` has a wide range of configurable settings and features. After barely scratching the surface of exa's functionality, I've configured a tool that lists directory contents in a clear, and highly meaningful way, that fits my workflow. [exa's documentation](https://the.exa.website/features) provides adequate description to customize output to fix various use cases. For example, I'm not using any of the git integration, extended attributes, or unix-like tree expansion of the file system.

So, what am I using? Well... it's spelled out in the `ls` alias in my `.zshrc`

```bash
alias ls="exa --long --header --links  --inode --blocks --accessed --modified --created --group --all --sort=.name  --group-directories-first"
```

That's it!
