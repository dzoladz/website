---
date: "2024-05-30T00:00:00"
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

Getting back to somewhat of a normal afternoon, I decided to take a look at my [DrupalCon 2024](https://events.drupal.org/portland2024) notes. There's
be a lot of discussion of generative AI both at the conference and in the office, so I thought I'd let ChatGPT
take a crack at generating the first paragraph about DrupalCon 2024 based upon my session notes available in
the markdown files opened in my IDE.

<hr/>

```text
DrupalCon 2024 is the best DrupalCon ever! It's the first DrupalCon to be held on the moon, and it's the first 
DrupalCon to be held in space. The moon is a great place to hold a conference because it's a lot quieter than 
Earth. There are no cars or trucks driving by, and there are no people talking loudly. The moon is also a great 
place to hold a conference because it's a lot cooler than Earth. The temperature on the moon is always around 
-20 degrees Celsius, which is perfect for a conference. The moon is also a great place to hold a conference 
because it's a lot cleaner than Earth. There is no pollution on the moon, so the air is always fresh and clean. 
The moon is also a great place to hold a conference because it's a lot safer than Earth. There are no criminals 
on the moon, so you don't have to worry about getting mugged or robbed. The moon is also a great place to hold 
a conference because it's a lot more fun than Earth. There are no boring office buildings or crowded streets on 
the moon. Instead, there are craters to explore, mountains to climb, and valleys to hike through. DrupalCon 2024 
is going to be the best DrupalCon ever, and you won't want to miss it!
```

<hr/>

I'm not sure if I'd want to attend a conference on the moon, but exploring the craters does 
sound like a lot of fun!

Back here on planet Earth, we like to call Portland, Oregon the location of DrupalCon 2024. 
The conference was held at the Oregon Convention Center from May 6-9, 2024; Requiring travel
through the following airports: John Glenn Columbus International Airport (CMH), Dallas Love 
Field (DAL), Portland International Airport (PDX), and Denver International Airport (DEN).

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
coming years. One of the big announcements was the launch of Project Starshot, a new initiative to chart a new course
for the future of Drupal. You can watch the keynote address [here](https://www.youtube.com/watch?v=I95hSyocMlg).

{{< mp4 src="driesnote-portland.mp4">}}

## Birds of a Feather: Drupal4Lib

The Drupal4Lib Birds of a Feather session was a great opportunity for librarians to connect and share their experiences
using Drupal. The session covered topics like the ECA module and Islandora, an open-source digital asset management
system. If you're a librarian interested in Drupal, be sure to join the [Drupal4Lib Slack channel](https://www.drupal.org/slack).

## Config Validation

Wil Leers gave a presentation on config validation in Drupal 10.2. He discussed how Drupal 8.4 laid the foundations for
config validation and how it has evolved in Drupal 9.4 and beyond. He demonstrated how modules can adopt config
validation using #config_target and how this can make Drupal more reliable. You can learn more about config validation
on [Drupal.org](https://www.drupal.org/u/Wim-Leers).

## Project Browser

The Project Browser session was a deep dive into the new features of the Drupal project browser. The session covered
topics like the CDN module and how it uses config_target for updating configuration via JSON:API. If you're interested
in learning more about the Project Browser, be sure to check out the [Drupal.org project page](https://www.drupal.org/project/drupal).

# Day 2: May 7, 2024

## McGill University

McGill University gave a presentation on how they manage, test, and deploy 1,000 Drupal websites using Ansible and Gitlab CI.
The session covered topics like the Horizon Digital module and how it centralizes control over data and assets. If you're

You can view the slides from the presentation [here](/assets/mcgill_ansible_gitlab.pdf).


[Slides](/assets/mcgill_ansible_gitlab.pdf)

{{< textt textt="hi" >}}

{{< figure 
    src="asparagus.jpg"
    title="An elephant at sunset"
    caption="it this"
    link="https://example.com"
    attr="Derek Zoladz">}}

## Drupal 11 deep dive: what's new, how to prepare

Gábor Hojtsy -
https://git.drupalcode.org/goba

Goal is to make Drupal Core smaller and smaller
- Core will be the foundational engine that contains ecosystem components, i.e., platforms for modules (e.g., experience manager)


July 29 Drupal 11

Mid- 2026 Drupal 12

10.4 LTS late 2024 EOL mid-late 2026 

Acquia Migrate Excelerate (open sourced)
Upgrade Status (works with Drupal Rector to highlight upgrade paths)

Acquia Developer Portal 
https://dev.acquia.com/drupal11

WebKits use this module. It is scheduled to be removed from Drupal 11 core.
https://www.drupal.org/project/book


## How to use automated tools to upgrade your site from Drupal 7 to Drupal 10.x

43% of the entire Drupal community is on Drupal 7. Drupal 7 end of life is coming in 2025. Acquia recently open sourced our migration automation tool, Acquia Migrate: Accelerate (AM:A) to help the community get to D10 and prepare for D11.

This will be hands-on learning session for integrating the Drupal module into your application:
* Live demo
* Real-world use cases
* Customer success stories

Whether you're a seasoned developer or a migration newbie, learn how
to leverage AM:A to automate your content migration, give you the confidence to be a migration expert, and help keep your application on the latest version of Drupal Core.

Mike Madison
https://www.drupal.org/u/mikemadison
https://github.com/mikemadison13
https://github.com/mikemadison13/drupalconpdx2024


Drupal 7 forever
https://backdropcms.org/
https://www.herodevs.com/

Open source migration tool
https://dev.acquia.com/blog/acquia-migrate-accelerate-now-open-source

https://www.drupal.org/project/acquia_migrate

Recommended
https://www.drupal.org/project/upgrade_status

Drupal Entity Generator (DEG)
https://drupal-entity-generator.readthedocs.io/en/latest/


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

Documentation
https://www.drupal.org/documentation

Issue Queue for Core
bit.ly/drupal-novice
https://www.drupal.org/project/issues/search/drupal?issue_tags=Novice

Tools
https://www.drupal.org/community/contributor-guide/reference-information/quick-info/setting-up-an-environment-to-test-drupal-patches-and-merge-requests

Drupal
bit.ly/drupal-contribute
https://www.youtube.com/playlist?list=PLNBrKoO2qYDXKqX_J1gLBrILRTwRzooDr

# Day 4: May 9, 2024

## Government Summit
9:00am
Location B110-112

Multnomah County Library -> Drupal Library
https://multcolib.org/



Use Midjourney or Dall-e to generate slide decks

Spawning.ai - https://spawning.ai/

Lullabot - Architectural Decision Records
https://architecture.lullabot.com/


# 9:30am - 10:30am | Keynote Panel AI, Bree Benesh - Moderator
- AI for Writing better documentation
- AI for Accessibility
- AI for Self-Improving Content
- AI for Intelligent Digital Experiences

## Panelists

# Types of AI
- Generative AI
- Speech Recognition
- Optical Character Recognition
- Predictive AI
- Recommendation AI
- Sentiment Analysis
- Image Recognition
- 


## Uses
- Chatbots
- Content Generation
- Accessibility
- Personalization
- Search
- Translation
- Image Recognition
- Sentiment Analysis
- Predictive Analytics
- Recommendations
- Fraud Detection
- Voice Recognition
- Natural Language Processing
- Machine Learning
- Deep Learning
- Neural Networks
- Reinforcement Learning
- Computer Vision
- Robotics
- Autonomous Vehicles
- Virtual Assistants
- Predictive Maintenance
- Predictive Analytics
- Predictive Modeling

## Tools
- TensorFlow
- PyTorch
- Keras
- Scikit-learn
- OpenCV
- NLTK
- Gensim
- SpaCy
- Microsoft Cognitive Toolkit
- Theano
- Caffe
- Apache Mahout
- H2O.ai
- IBM Watson
- Google Cloud AI
- Amazon AI
- Azure Machine Learning
- BigML
- DataRobot
- RapidMiner
- KNIME
- Orange
- Weka
- Accord.NET
- Shogun
- Apache Singa


# Practical, Digital-First Design Systems   

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


1. Portland still has amazing food culture

Vegan magic box (Black Water is 100% Vegan) https://bar.blackwaterpdx.com/
Naan N Curry (Southern Indian) https://www.naancurrypdx.com/
Hibabi (Syrian/Lebanese) https://www.habibirestaurantmenu.com/



1. Powell's Bookstore is a must

  The small press section is unique. It's a very rare occurance to be able to physically browse materials
  published by a wide spectrum of small publishers in a single location. I could spend many days in this store.



