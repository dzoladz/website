
---
date: "2019-06-06T11:00:00"
draft: false
tags: ["applications"]
title: "Farewell, Nano"
math: false
summary: "Time to retire the venerable command-line text editor."

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

Forever, I've used `nano` as my command-line text editor. I've never had an issue with it. In fact, it's been so reliable that I've keep it around much longer than I should have. It still works well for most of my needs, but it's time to expand my suite of skills and learn something new.

That's why I'm switching to `vim`.

Out-of-the-box, `vim` is a _tabula rasa_, a blank slate, and it feels oddly empty. To fill this vacuum, my first step in making the transition was to explore plugin managers. Of course, this is following an introductory period to learn the basics. If I was going to successfully make the switch, I was going to need to first personalize my instance `vim`.

I selected Tim Pope's [pathogen.vim](https://github.com/tpope/vim-pathogen) as my plugin manager. `pathogen.vim` allows for each plugin to be placed into its own version-controlled directory and loaded at runtime. Installing a plugin is straightforward: `git clone` into `~/.vim/bundle/`. Simple, maintainable, elegant.

Here are a few of the plugins that comprise my base:

- [jellybeans.vim](https://github.com/nanotech/jellybeans.vim): Because everyone needs a cheerful, dark-mode enabled, color scheme.
- [nerdtree.vim](https://github.com/scrooloose/nerdtree): If you're going to be using `vim` for any amount of time, you'll want to have a file explorer.
- [fugitive.vim](https://github.com/tpope/vim-fugitive): A way more advanced git wrapper than I currently need, but a rich avenue for exploration and growth. I'm basically using this plugin to display git information in the `'statusline'` via...
- [lightline.vim](https://github.com/itchyny/lightline.vim): In a nutshell, an easy to use and highly configurable `'statusline'` plugin.

Feel free to take [my initial configuration](https://github.com/dzoladz/.vim) for a spin!
