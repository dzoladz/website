+++
date = "2020-03-14T11:00:00"
draft = false
tags = ["conferences", "Applications"]
title = "code{4}lib - Pittsburgh, PA"
math = false
summary = "At the emergence of a global pandemic."

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

### Lots of Firsts at Code{4}lib 2020

Code{4}lib is the only major conference that I've attend with a single track. Most conferences are multi-track. At a multi-track conference, attendees gather for a keynote presentation to kick-off the event. But after that collective experience, everyone develops a self-selected path through simultaneously occurring presentations and activities. At Code{4}lib, all attendees experience the same sequence of sessions, lightning talks, breakouts, and keynotes presentations. There's a definitively stronger sense of community that emerges with a single-track conference. As attendees discuss sessions - through the filters of their own local context and professional focus - a richer understanding of each topic develops.

This conference also marks the first time that I've worked on a committee for a national conference. All of my previous conference planning experiences have been either at the state, regional, or institutional-level. As a member of the Website Working Group for the [2020 conference](https://2020.code4lib.org/), our team focused mainly on content strategy for web properties and improving the overall experience for on-site and remote attendees, speakers, sponsors, and a host of other interested parties that will stumble upon the content in the coming weeks and months. Our team contributed a number of significant improvements to the overall accessibility of the conference website, including: (1) multiple adjustments to the document structure, (2) removing situations of skipped heading to ease screenreader traversal, and whenever possible (3) swapping static content with variable references, so that next year's working group will be able to customize the conference website more fully by simply updating the content in the site's `data.yml` file.

Another first? How about navigating the terrain when your conference coincides with the emergence of the global pandemic: __COVID-19__. Impossible to anticipate, but major crises highlight the spectrum of financial and logistical realities faced by any organization that hosts a national conference. Hats off to the Local Planning Committee, as they did a spectacular job of keeping on top of CDC recommendations and guiding with definitive leadership. And the Streaming Video Committee, they kept the [remote presentations](https://www.youtube.com/playlist?list=PLzGHg-1qAr4BxO2TzF9wiFcXVTEn1rRYM) connected and engaged with flawless momentum. Bravo.

### Food, 'Cause the Answer is Always "Yes"

I ❤️ food. One of the things that I savor about visiting another city - for a conference or otherwise - are those brief moments that I actually get to experience it's uniqueness. When I visited Portland, Oregon several years ago, the food culture was truly exceptional. Portland set a rather high bar for my future gastronomic explorations. But, a treasure can be uncovered anywhere. One pleasant surprise along my conference trek has been Minneapolis, Minnesota. Quite literally, the best breakfast tostada I've ever eaten was at [Mercury](https://mercurympls.com/), which is less than a city block from the light rail station at Nicollet Mall.

Unfortunately, Pittsburgh was slightly underwhelming. I did manage to discover a tasty sandwich shop, [Gaucho's Parrilla Argentina ](https://www.eat-gaucho.com/) in the Strip District, and the downtown location of [Nicky's Thai Kitchen](http://www.nickysthaikitchen.com/) had a refreshing ginger-infused hot sake that was entirely welcome after a full day.

### Hotel Oddities

A rather large _sinkhole_ exposed the bowels of the city, and swallowed a city bus in October 2019, remained unrepaired in front of the Westin hotel.
![Pittsburgh port authority bus projecting upward from a sinkhole in the middle of a downtown street](https://9b16f79ca967fd0708d1-2713572fef44aa49ec323e813b06d2d9.ssl.cf2.rackcdn.com/1200x/20191028dsSinkholePATBusLocal03-2-1572277030.jpg "Pittsburgh port authority bus projecting upward from a sinkhole in the middle of a downtown street")

And the _elevator_ controls were... um, peculiar. Rather than attempting to describe it myself, I'll just point to the following 5 minute lightening talk that does a much better job than I can:

- [Expectations and Conventions: A code{4}lib Elevator Story](https://youtu.be/0URpVt0-iVQ?t=9815).

Yes, it really is a fun _and_ informative talk that's worth your next coffee break.

### Lots of Projects that I'll Follow-up on:

Before heading to the conference, I was already in the process of spinning up the digital asset management system [Hyku](https://hyku.samvera.org/) on a t3-large EC2 instance. Having just finished writing a `docker-compose-ohn.yml` file to set up an instance of Hyku behind the reverse proxy [Traefik](https://containo.us/traefik/) and using [Portainer](https://www.portainer.io/) as a container management tool, I was just beginning to explore Hyku's possibilities.

As such, I stopped by the [Samvera](https://samvera.org/) community table during one the breaks for a brief chat about the [Hyku for Consortia](https://www.hykuforconsortia.org/) project.

![Hexagon-shaped sticker showing Hyku for Consortia logo](/website/post/2020code4lib/hyku_for_consortia.png "Hexagon-shaped sticker showing Hyku for Consortia logo")

![Hexagon-shaped sticker showing Hyku for Consortia logo]({{ "hyku_for_consortia.png" | relURL }} "Hexagon-shaped sticker showing Hyku for Consortia logo")

The main focus of the Hyku for Consortia work is to implement a series of changes to the permissions of Hyku. While Hyku is architected as a multi-tenant application right out of the box, there is no current method to provide a group of users with the ability to work across tenants. The Hyku for Consortia project aims to create this feature to facilitate cross-consortial collaborations, as well as allowing the development of administrative governance bodies, say "a standards and review body", which could provide guidance and assistance throughout all of the tenants hosted on a single Hyku instance. The project has partnered with [Notch8](https://www.notch8.com/) out of San Diego to complete the feature development.

### ... Just a Few Others
So many tools, so little time.

[HTTP Toolkit](https://github.com/httptoolkit)  
Is this a mashup of [Wireshark](https://www.wireshark.org/) and [Fiddler](https://www.telerik.com/fiddler), but more intuitive? We'll find out soon enough :)

[Preserve this Podcast](https://github.com/mnylc/preservethispodcast)  
Likely of more interest to public libraries, setting up a DIY podcast preservation workshop might appeal to communities with an interest in audio or citizen journalism. Recently, I've been much more focused on the applicability of [The Carpentries](https://carpentries.org/) workshops for academic technical services departments... especially for mid-sized academic libraries located within reasonable geographic proximity to any major metropolitan area. These skills need to be acquired now.

[Wagtail](https://github.com/wagtail/wagtail)  
It's an open source content management system built on [Django](https://www.djangoproject.com/). It can be used to create simple apps that can be embedded into link resolvers, or other library platforms, to allow patrons to report missing PDFs, broken links, or other problematic content within a vendor's platform. Input capture mechanisms can be coded using client-side Javascript.

[BrowserStack](https://www.browserstack.com/)  
Execute automated browser tests as part of a CI/CD pipeline. There's a free-tier planning for testing open source projects.

[Helium](https://github.com/mherrmann/helium)  
An alternative to [Selenium](https://www.selenium.dev/) for driving a browser. Useful for application testing and automating routine chores. I'm looking forward to giving this tool a test drive. The simplified API appears magical.  
