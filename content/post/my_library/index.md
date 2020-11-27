+++
date = "2019-10-03T11:00:00"
draft = false
tags = ["applications"]
title = "Overview of My Personal Library"
math = false
summary = "Building a personal library from scratch: Hardware, Networking, and ILS."

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

On a day-to-day basis, I work with the [Consortium of Ohio Libraries](http://info.cool-cat.org/) on their open-source ILS [Evergreen](https://evergreen-ils.org/). Whether it's configuring new circulation policies, adjusting global system settings, or writing SQL to batch update item attributes, I've explored a significant chunk of Evergreen over the last 3 years. But it's an understatment to say that Evergreen is a massive application. There's still plenty of uncharted functionality.
   
Evergreen's architecture is designed for multi-tenancy out-of-the-box and built to scale to very large consortia. In the United States, it's the platform for a number of large public library consortia. For a personal library, it's overkill. Developing a personal library is also an opportunity to explore the setup and administer another ILS.

For these reasons, I chose another well-known open source ILS used most often by stand-alone public libraries as the foundation for my personal library: [Koha](https://koha-community.org/).

Goals for the personal library projected included:

* Low stakes copy and original MARC cataloging experience
* Developing data migration skills (e.g. Koha to [FOLIO](https://www.folio.org/))
* Diversifying my ILS administration 
* Design and build ILS infrastructure and networking from scratch

I'll be cataloging my personal collection of library-related books on my local network using the following hardware.
<video controls src="/post/my_library/koha_server.mp4"></video>
