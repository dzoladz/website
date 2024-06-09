---
date: "2024-12-24T00:00:00"
draft: true
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

<hr/>

```text
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
```

<hr/>

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

# Day 1: May 6, 2024

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

## Birds of a Feather: Drupal4Lib

The Drupal4Lib Birds of a Feather session was a great opportunity for librarians and cultural heritage professionals 
to connect and share their experiences using Drupal. The session covered topics like the 
[Event - Condition - Action](https://www.drupal.org/project/eca) (ECA) module and [Islandora](https://www.islandora.ca/)
, an open-source digital asset management system built on top of Drupal Core. If you're a librarian interested in Drupal
, be sure to join the [Drupal4Lib Slack channel](https://www.drupal.org/slack) and search for other folks in the 
`drupal4lib` community.

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

# Day 2: May 7, 2024



{{< figure 
    src="asparagus.jpg"
    title="Burgerville advertisement"
    caption="Portlanders, have you been waiting a long time?"
    link="https://www.burgerville.com/"
    attr="Derek Zoladz">}}

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


# STOPPED HERE ----------------



## Drupal 11: What's New

[Gábor Hojtsy](https://git.drupalcode.org/goba) led this session discussing the upcoming features of Drupal 11. While
features are always welcome, the key takeaway from this session is a rethinking of Drupal Core. Core will become the 
foundational engine that supports "ecosystems", refining the focus of Core to be a platform for modules. Drupal Core
will get smaller and smaller, as one-off modules intended to provide functionality, not support entire ecosystems of
modules, are removed from Core and shifting into community contributions.

The [Book Module](https://www.drupal.org/project/book) is an example of a module - used by OPLIN Webkits to provide 
hierarchical structure of nodes - scheduled to be removed from Core ore in the Drupal 11 release  after 22 years.

| Release Date  | Version         |
|---------------|-----------------|
| July 29, 2024 | Drupal 11       |
| Late 2024     | Drupal 10.4 LTS |
| July 2026     | Drupal 12       |

Long-Term Support (LTS) releases of Drupal Core are available. I was familiar with LTS releases in the Debian space, but
I was not aware of LTS releases of Drupal Core. LTS offers and additional 2 years of support. The end-of-life (EOL) of
Drupal 10.x is slated for mid-late 2026.

## From Drupal 7 to Drupal 10

Drupal 7 will be end-of-life in January 2025. Performing a migration from Drupal 7 to modern Drupal was a topic sitting
behind almost every presentation at the conference. This session put some hard data behind the community's obvious
concerns. As of January 2024, nearly 43% of the entire Drupal community is running on Drupal 7 with EOL roughly 6 months
out. The main point of this session was to announce that [Acquia](https://www.acquia.com/) recently open sourced their 
migration automation tool, Acquia Migrate: Accelerate (AM:A) to help the community migrate away from Drupal 7 with 
confidence.

[Mike Madison's](https://www.drupal.org/u/mikemadison) Recommended Links
- [Herodevs: Drupal 7 forever](https://www.herodevs.com/)
- [Acquia Migrate: Accelerate (AM:A)](https://www.drupal.org/project/acquia_migrate)
- [Upgrade Status](https://www.drupal.org/project/upgrade_status)
- [Drupal Entity Generator (DEG)](https://drupal-entity-generator.readthedocs.io/en/latest/)
- [Drupal Rector](https://www.drupal.org/project/rector)
- [Acquia Developer Portal](https://dev.acquia.com/) 

And with the anxiety surrounding the migration from Drupal 7 to Drupal 10, it's worth noting an earlier session on the
first day of the conference announcing [RetroFit](https://retrofit-drupal.com/). RetroFit provides several compatibility
layers that will allow Drupal 7 code to run within a Drupal 10 environemnt.

<iframe 
  width="625" height="350"
  style="margin: 0 auto; display: block;"
  src="https://www.youtube.com/embed/C92LWKVhLmI?si=_lRDSGu446Traqwi"
  frameborder="0"
  allowfullscreen>
</iframe>


# Day 3: May 8, 2024

## Drupal Project Initiatives Keynote

### Drupalize.me
(1) Issue Queues
https://drupalize.me/blog/dcpdx-2024-iq

Contributions linked to Drupal.org User Profile
https://www.drupal.org/u/dzoladz

### Gander
Performance Testing

tag1.com/gander/ten-percent-faster

https://github.com/tag1consulting


### Gitlab CI
https://project.pages.drupalcode.org/gitlab_templates/

### Automatic Updates

drupal.org/projects/automatic_updates

### ECA

Drupal Project
https://www.drupal.org/project/eca

UI
https://bpmn.io/

Guide
https://ecaguide.org/

### New Navigation
Left sidebar navigation, i.e., modern navigation patterns

uses layout builder to "drag and drop" navigation components

navigation.module -> in core 

### Single directory components

"site building" ?


## First Contribution Workshop

- [Drupal Documentation](https://www.drupal.org/documentation)
- [Novice Issue Queue for Core](https://www.drupal.org/project/issues/search/drupal?issue_tags=Novice)
- [Setting Up a Development Environment](drupal.org/tools)

## Downtown Portland

TriMet system

1. Portland still has amazing food culture

Vegan magic box (Black Water is 100% Vegan) https://bar.blackwaterpdx.com/
Naan N Curry (Southern Indian) https://www.naancurrypdx.com/
Hibabi (Syrian/Lebanese) https://www.habibirestaurantmenu.com/



1. Powell's Bookstore is a must

  The small press section is unique. It's a very rare occurance to be able to physically browse materials
  published by a wide spectrum of small publishers in a single location. I could spend many days in this store.

# Day 4: May 9, 2024

The Government Summit was in the morning.

# Types of AI
- Generative AI
- Speech Recognition
- Optical Character Recognition
- Predictive AI
- Recommendation AI
- Sentiment Analysis
- Image Recognition

Multnomah County Library -> Drupal Library
https://multcolib.org/


[Drupal Resources for Public Libraries](https://groups.drupal.org/libraries/resources)


[Lullabot - Architectural Decision Records](https://architecture.lullabot.com/)



## Practical, Digital-First Design Systems   

Website modernization (21st Centruy Integrated Digital Experience Act)
https://digital.gov/resources/delivering-digital-first-public-experience/

USWDS maturity model
https://designsystem.digital.gov/maturity-model/

## Bixal + USWDS
https://designsystem.digital.gov/


USWDB implementation for the bixal theme

Component Guide? Implementations in Drupal?
https://storybook.js.org/

Storybook components into Drupal namespace

New Bixal Preview
- https://preview.bixal.com/

F18
https://18f.gsa.gov/

Cloud Pages
https://cloud.gov/pages/

## Promet Source
https://www.prometsource.com/

### LLM RAG
Retrieval Augmented Generation (RAG) for LLMs

RAG is an architectural approach that improves the efficacy of large language model (LLM) applications by 
leveraging custom data. Promet Source uses a Solr index of the library's website to provide contextual data to 
clarify the customers request.


## LA Water

User Journey




# Fin - Key Takeaways

1. Drupal as a "digital experience builder", not merely a CMS

  Coming into the conference, my experience with Drupal was limited to about 20 hours of targeted
  troubleshooting for Laura Solomon. 

  Extending core with modules, and now with recipes, etc...

1. Leaving ready to contribute

  There are several requirements that must be met to participate in the development of Drupal.
  First, you need to have a Drupal.org user account and it *must* be confirmed.
  Second, you need to familiarize yourself with the codebase, issues, and general working preferences of the Drupal community.
  Third, you need to medium to discuss day-to-day Drupal and potential solutions with the community for feedback and best practices.


1. Learning the terminology used by "Site Builders" is a must
  
  It's the only way to bridge the gap between developers and the intricate needs to "site builders"
  for custom code to support customer needs.






