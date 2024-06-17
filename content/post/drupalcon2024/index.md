---
date: "2024-05-21T00:00:00"
draft: false
tags: ["drupal", "conferences", "applications"]
title: "DrupalCon 2024: Portland, Oregon"
math: false
summary: "First experiences at DrupalCon 2024"

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
image:
   preview_only: false
---

Getting back to somewhat of a normal afternoon, I decided to take a look at my [DrupalCon 2024](https://events.drupal.org/portland2024) notes. There
has been a lot of discussion around generative AI, both at the conference and in the OPLIN office, so I thought I'd 
let ChatGPT take a crack at generating the introductory paragraph about DrupalCon 2024. Based upon my session note 
files currently open in my IDE (Integrated Development Environment), here is the result...

<div style="display: block;">

<div style=" padding: 1em; margin: 1em; font-family: monospace; font-size: 14px;">
DrupalCon 2024 is the best DrupalCon ever! It's the first DrupalCon to be held on 
the moon, and it's the first DrupalCon to be held in space. The moon is a great 
place to hold a conference because it's a lot quieter than Earth. There are no 
cars or trucks driving by, and there are no people talking loudly. The moon is 
also a great place to hold a conference because it's a lot cooler than Earth. The 
temperature on the moon is always around -20 degrees Celsius, which is perfect 
fora conference. The moon is also a great place to hold a conference because it's
a lot cleaner than Earth. There is no pollution on the moon, so the air is always 
fresh and clean. The moon is also a great place to hold a conference because it's 
a lot safer than Earth. There are no criminals on the moon, so you don't have to 
worry about getting mugged or robbed. The moon is also a great place to hold a 
conference because it's a lot more fun than Earth. There are no boring office 
buildings or crowded streets on the moon. Instead, there are craters to explore, 
mountains to climb, and valleys to hike through. DrupalCon 2024 is going to be 
the best DrupalCon ever, and you won't want to miss it!
</div>
</div>

Exploring the craters on the moon does sound like a lot of fun!

Back here on planet Earth, we like to call Portland, Oregon the location of DrupalCon 2024. 
The conference was held at the Oregon Convention Center from May 6-9, 2024; requiring travel
through the John Glenn Columbus International Airport (CMH), Dallas Love Field (DAL), Portland 
International Airport (PDX), and Denver International Airport (DEN).

{{< figure 
    src="flight-map.png"
    title="4,683 miles travelled for DrupalCon 2024"
    alt="map of the united states indicating the geographic location of traveled airports"
    attr="flightmapper.io" 
    attrlink="https://flightmapper.io/maps/dzoladz" >}}

<div style="height: 0.5em; display: block;"></div>
<hr/>

# Day 1: May 6, 2024

<hr/>
<div style="height: 0.5em; display: block;"></div>

## Driesnote

Dries Buytaert, the founder of Drupal, gave the keynote address at DrupalCon 2024. He talked about the history of
Drupal and how it has evolved over the years. He also discussed the future of Drupal and what we can expect in the
coming years. One of the big announcements was the launch of [Project Starshot](https://www.drupal.org/starshot), a 
new initiative to create an out-of-the-box CMS (Content Management System) experience for Drupal that includes the 
latest features of Drupal Code combined with a curated suite of best-in-class community contributed modules for 
common features. An unstated goal of this effort would be to for the Drupal community to have a competitive product
to the Wordpress experience.

[Presentation slides are available](https://dri.es/files/state-of-drupal-may-2024.pdf).

<iframe 
  width="625" height="350"
  style="margin: 0 auto; display: block;" 
  src="https://www.youtube.com/embed/I95hSyocMlg?si=d8BswF9XPr249Y50&amp;start=1185"
  frameborder="0"
  allowfullscreen>
</iframe>

<br/>

## Birds of a Feather: Drupal4Lib

The Drupal4Lib Birds of a Feather session was a great opportunity for librarians and cultural heritage professionals 
to connect and share their experiences using Drupal. The session covered topics like the 
[Event - Condition - Action](https://www.drupal.org/project/eca) (ECA) module and [Islandora](https://www.islandora.ca/)
, an open-source digital asset management system built on top of Drupal Core. If you're a librarian interested in Drupal
, be sure to join the [Drupal4Lib Slack channel](https://www.drupal.org/slack) and search for other folks in the 
`drupal4lib` community.

<div style="height: 0.5em; display: block;"></div>

## Config Validation

Wil Leers gave a presentation on config validation in Drupal 10.2. He discussed how Drupal 8.4 laid the foundations for
config validation and how it has evolved in Drupal 9.4. He demonstrated how modules can adopt config validation using 
`#config_target` and how this can make Drupal more reliable. Because validating configuration in Drupal is a vast topic,
I've linked Wil's presentation from last year's DrupalCon Pittsburgh.

<iframe 
  width="625" height="350"
  style="margin: 0 auto; display: block;"
  src="https://www.youtube.com/embed/mat99-lWA_U?si=_0EiKC4ZS2TTdsgp"
  frameborder="0"
  allowfullscreen>
</iframe>

<br/>

## Project Browser

The Project Browser session was a deep dive into the new features of the Drupal 
[Project Browser](https://www.drupal.org/project/project_browser) initiative. Project Browser makes it easy for site 
builders to find modules. Once the modules is installed, the project browser lives inside the Drupal site itself and
provides a marketplace-like experience for modules.

{{< figure 
    src="project_browser.png"
    title="Project Browser design sets"
    alt="current figma designs for the minimum viable product"
    attr="Project Browser Team" 
    attrlink="https://www.figma.com/design/1Z8xrcP2zgnO6BXlu9ZeQ5/Project-browser?node-id=964-4805" >}}

<div style="height: 0.5em; display: block;"></div>
<hr/>

# Day 2: May 7, 2024

<hr/>
<div style="height: 0.5em; display: block;"></div>

## McGill University

McGill University gave a presentation on how they manage, test, and deploy 1,000 Drupal websites using Ansible and 
Gitlab CI. The best way to understand the gist of this presentation is to peruse the 
[presentation slides](mcgill_ansible_gitlab.pdf).

{{< figure 
    src="mcgill.png"
    title="Screenshot of Thomas Fline's Slides"
    caption="Screenshot of Thomas Fline's Slides"
    link="mcgill_ansible_gitlab.pdf"
    attr="Thomas Fline">}}

<div style="height: 0.5em; display: block;"></div>

## Drupal 11: What's New

[Gábor Hojtsy](https://git.drupalcode.org/goba) led a session discussing the upcoming features of Drupal 11. While new features are always welcome, 
the key takeaway from this session is a complete rethinking of the function of Drupal Core. Core will become a 
foundational engine that supports "ecosystems"; thus, refining the focus of Drupal Core to be a platform for modules
rather than a storehouse for the best modules in the Drupal community. As a result, Drupal Core will get smaller and 
smaller as one-off modules providing unique functionality (i.e., not in support of entire ecosystems of
modules) are removed from the core and shifted into the community contributions space.

Used by OPLIN Webkits to provide hierarchical structure of nodes, the [Book Module](https://www.drupal.org/project/book) is an example of a module 
scheduled to be removed from core in the Drupal 11 release. It has been a core module for 22 years.

For reference, here is the upcoming release schedule:

| Release Date  | Version         |
|---------------|-----------------|
| July 29, 2024 | Drupal 11       |
| Late 2024     | Drupal 10.4 LTS |
| July 2026     | Drupal 12       |

I was familiar with LTS (Long-Term Support) releases from the Ubuntu linux space, but I did not know that LTS releases 
of Drupal Core were available. LTS releases of Drupal Core offer an additional 2 years of support, which extends the 
end-of-life (EOL) of Drupal 10.x into late 2026.

<div style="height: 0.5em; display: block;"></div>

## From Drupal 7 to Drupal 10

Performing a migration from Drupal 7 to a modern version of Drupal was a recurring topic at the conference. It was rare
for a session **not** to mention that Drupal 7 will be end-of-life in January 2025. This session put some hard data 
behind the community's obvious concerns. As of January 2024, nearly 43% of the entire Drupal community was running 
Drupal 7. That's a large percentage of the community running production applications on top of a release with an 
end-of-life that's roughly 6 months away.

The main point of [Mike Madison's](https://www.drupal.org/u/mikemadison) session was to announce that 
[Acquia](https://www.acquia.com/) recently open sourced their automated migration toolkit. [Acquia Migrate: Accelerate (AM:A)](https://www.drupal.org/project/acquia_migrate)
was make available to help the Drupal community migrate away from Drupal 7 with confidence.

Other Recommended Links:

- [Herodevs: Drupal 7 forever](https://www.herodevs.com/)
- [Upgrade Status](https://www.drupal.org/project/upgrade_status)
- [Drupal Entity Generator (DEG)](https://drupal-entity-generator.readthedocs.io/en/latest/)
- [Drupal Rector](https://www.drupal.org/project/rector)
- [Acquia Developer Portal](https://dev.acquia.com/) 

And with the anxiety surrounding a migration from Drupal 7 to Drupal 10, it's worth noting an earlier session 
on the first day of the conference announcing [RetroFit](https://retrofit-drupal.com/). RetroFit provides several compatibility
layers that will allow Drupal 7 code to run within a Drupal 10 environment.

<iframe 
  width="625" height="350"
  style="margin: 0 auto; display: block;"
  src="https://www.youtube.com/embed/C92LWKVhLmI?si=_lRDSGu446Traqwi"
  frameborder="0"
  allowfullscreen>
</iframe>

<br/>
<hr/>

# Day 3: May 8, 2024

<hr/>
<div style="height: 0.5em; display: block;"></div>

The morning keynote provided an update on the Drupal Project Initiatives. Being as this is my first Drupal conference,
my knowledge of each initiative is negligible. A link to each project initiative is provided below for future 
reference:  

**[Drupalize.me](https://drupalize.me/blog/dcpdx-2024-iq)**
  
  Development of issue queues linked to a Drupal Association user. A [blog post](https://drupalize.me/blog/dcpdx-2024-iq)
  from the Portland DrupalCon is available.

**[Gander](https://www.drupal.org/docs/develop/automated-testing/performance-tests)**
  
  Performance Testing for Drupal applications, lead by [Tag1 Consulting](https://github.com/tag1consulting).
  A blog post from initial tests indicate a [ten percent speed improvement](tag1.com/gander/ten-percent-faster)

**[Gitlab CI Templates](https://project.pages.drupalcode.org/gitlab_templates/)**

  The GitLab Templates project drives the GitLab CI integration for all Drupal contrib modules.

**[Automatic Updates](https://www.drupal.org/about/starshot/initiatives/automatic-updates)**

  Automatically install updates in Drupal to: (1) lower the total cost of ownership of maintaining a Drupal site, (2) 
  improve the security of Drupal sites in the wild, and (3) lower the barrier to entry to using Drupal.

**[ECA (Event-Condition-Action)](https://www.drupal.org/project/eca)**

  ECA gets triggered on every Drupal event, allowing for the creation of rules to trigger related
  actions. ECA requires a business process model and notation front-end (e.g., [BPMN](https://bpmn.io/)) to design
  rules and workflows. An [ECA Guide](https://ecaguide.org/) is available for perusal.

Additional discussion of single directory components, left sidebar navigation, and using layout builder to enable 
"drag and drop" components into a layout rounded out the morning keynote.

<div style="height: 0.5em; display: block;"></div>

## First Contribution Workshop

During the workshop, I was able to have my Drupal.org account verified. Once verified, I was able to create a user
profile ([dzoladz](https://www.drupal.org/u/dzoladz)) and establish an organizational entity for the Ohio Public 
Library Information Network ([OPLIN](https://www.drupal.org/ohio-public-library-information-network)).

Other Recommended Links:

- [Drupal Documentation](https://www.drupal.org/documentation)
- [Novice Issue Queue for Core](https://www.drupal.org/project/issues/search/drupal?issue_tags=Novice)
- [Setting Up a Development Environment](drupal.org/tools)

<div style="height: 0.5em; display: block;"></div>

## Downtown Portland

The TriMet system is easy to navigate, the food culture is amazing (e.g, [Black Water](https://bar.blackwaterpdx.com/)),
and [Powell's City of Books](https://www.powells.com/locations/powells-city-of-books) is an absolute must. The small 
press section is extremely unique. It's a very rare occurrence to be able to physically browse materials published by 
a wide spectrum of small publishers in a single location. I could spend many days in this store.

<div style="height: 0.5em; display: block;"></div>
<hr/>

# Day 4: May 9, 2024

<hr/>
<div style="height: 0.5em; display: block;"></div>

The Government Summit was in the morning. I learned that the [Multnomah County Public Library](https://multcolib.org/)
uses Drupal in production for their public-facing web presence. I also discovered that there are a wide array of 
available resources related to Drupal and public libraries: [Drupal Resources for Public Libraries](https://groups.drupal.org/libraries/resources).

By this time in the conference, I was not in the mood to hear anything else about artificial intelligence or ChatGPT in
particular. So when the discussion once again moved to classifications of AI (i.e., Generative AI , Speech Recognition, 
Optical Character Recognition, Predictive AI, Recommendation AI, Sentiment Analysis, and Image Recognition), I elected
to review [Lullabot's Architectural Decision Records](https://architecture.lullabot.com/).

<div style="height: 0.5em; display: block;"></div>

## Practical, Digital-First Design Systems   

Alright, I'm getting tired to writing this summary. I'm dropping these links here to explore at a future date.

- [21st Century Integrated Digital Experience Act](https://www.cio.gov/policies-and-priorities/21st-century-IDEA-act/)
- [Digital-First Design Systems](https://digital.gov/resources/delivering-digital-first-public-experience/)
- [United States Web Design System maturity model](https://designsystem.digital.gov/maturity-model/)
- [Storybook](https://storybook.js.org/)
- [Bixal Theme - Preview](https://preview.bixal.com/)
- [F18](https://18f.gsa.gov/)
- [Cloud Pages](https://cloud.gov/pages/)
- [Promet Source](https://www.prometsource.com/)
