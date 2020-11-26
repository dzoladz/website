+++
date = "2020-10-28T11:00:00"
draft = false
tags = ["conferences"]
title = "2020... the year of the great learning"
math = false
summary = "Tools & Services for a virtual conference"

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

One upside of 2020 has been the expansion of learning opportunities. Conferences with pricey registration fees or cost-prohibitive for travel reasons have become real opportunities, as library and library-adjacent conferences and workshops transition to online delivery. I've registered for three times as many conference as I would in a typical year, but I've also not attended most of those events. When the event actually gets here, there's always other work that I find a better use my time. I guess that's a consequence of free registration - although I'm not sure how it has been possible for so many organizations to offer free registration for their online events this year. There are plenty of tangible costs associated with a delivery of a fully online conference. Anyway... that's all a divergence from the intent of this post, which is to reflect upon my work for the [2020 ALAO Conference](https://2020.alaoweb.org/)

As the great learning of 2020 continues to bloom, a second upside has been the number of opportunities that have been granted to me to put the complete spectrum of my technical abilities into practice. While unexpected, serving as the Chair of the Website Working Group and Technical Lead for the Academic Library Association of Ohio (ALAO) annual conference - ALAO's first ever fully online conference - has been a highlight for me.

Leading the Website Working Group was a wonderful opportunity to:

- [1] expand the technical capacity and web property portfolio of ALAO
- [2] establish a GitHub organization to warehouse and share useful scripts and application code between ALAO members
- [3] obtain a non-profit Slack account for the organization, with additional features and increased limits
- and, [4] apply for an open source project account with Netlify to host application deployments for the 2020 conference website.

Volunteer projects like this one always provide an opportunity to exercise and develop my leadership abilities, mentor younger colleagues, and further enrich and solidify my project management capabilities.

### Team
Members of the 2020 Website Working Group are as follows:

- David Green (State Library of Ohio)
- Melissa Hill (Ohio Wesleyan University)
- Ken Irwin (Miami University)
- Ryan Scott (Columbus State Community College)
- Zach Walton (The Ohio State University)

The Website Working Group was responsible for applying the overall conference theme to the website, while adding features and functionality to the source code as gaps were discovered or a new set of needs arose. One of our stated goals was to make the site more plug-and-play for next year's teams. We did this by replacing any hardcoded values throughout the source code with a centrally-located set of variables. In fact, the majority of variables controlling the website's behavior and internal logic are contained in a single file at this point. Ideally, this will result in vastly reduced development times for next year's conference website.

Over the course of building the website, our primary method of communication was the `#conference-website` channel of the ALAO Slack workspace. Idea exchange, quick triage, and fast feedback were a breeze via Slack. Complex troubleshooting and issues requiring more in-depth discussion were held of our regularly scheduled meeting. Project management was mainly facilitated through Github’s native tooling, via issue creation, issue assignment of responsibilities, and a wiki for setting the agenda for our regular meetings.

Our team worked in 3-week sprints over the course of a few months to bring the conference site together. Each sprint would begin with an hour-long meeting to review our progress, discuss any open issues, and set goals and priorities for the next sprint. Since our team was a combination of experienced developers and some folks who were entirely new to static site generators and source code versioning tools, the 3-week pace worked out surprisingly well for the whole team. For the less experienced members of the team, there was enough cushion to begin to explore the source code, generate a list of initial questions, and pursue self-guided learning to get up-to-speed... while keeping just enough momentum under the project for the more experienced team members to maintain interest and continue to drive the project forward. Unfortunately, there are far too few hands-on mentorship opportunities for librarians to build a rich depth of technical knowledge that rivals the expertise of information technology staff. For the members of the Website Working Group, the experience of sharing knowledge and hard skills during the development of the conference website will slowly manifest in the comprehensiveness and degree of digital projects at each team member's local institution.

It's worth noting that I underestimated the time commitment required to complete this project by roughly 30 hours. I anticipated 60 hours, but the actual time was closer to 90 hours. Although a considerable portion of the additional time occurred due to adding features and functionality that were not envisioned at the onset of the project, it's a reminder to myself to do a better job controlling the scope of the project or padding my estimates a bit more generously to allow for some expansion as the project matures.

```buildoutcfg
➜  2020.alaoweb.org git:(master) git-fame --cost hours
Processing: 100%|███████████████████████████████████████████████████████████████████████████| 480/480 [00:31<00:00, 15.32file/s]
Total commits: 831
Total ctimes: 2866
Total files: 377
Total hours: 89.2
Total loc: 505996
| Author          |   hrs |    loc |   coms |   fils |  distribution   |
|:----------------|------:|-------:|-------:|-------:|:----------------|
| dzoladz         |    51 | 475569 |    445 |    252 | 94.0/53.5/66.8  |
| Ken Irwin       |    27 |  29319 |    261 |    100 | 5.8/31.4/26.5   |
| Zach Walton     |     2 |    785 |     13 |      4 | 0.2/ 1.6/ 1.1   |
| davidg          |     3 |    253 |     16 |     16 | 0.1/ 1.9/ 4.2   |
| Nassaubound     |     2 |     68 |     16 |      4 | 0.0/ 1.9/ 1.1   |
| David W. Green  |     2 |      2 |      8 |      1 | 0.0/ 1.0/ 0.3   |
| Derek C. Zoladz |     2 |      0 |     72 |      0 | 0.0/ 8.7/ 0.0   |
```

As illustrated in the above output from [git fame](https://github.com/casperdcl/git-fame), Ken Irwin made significant contributions to the development of 2020 conference website. Ken's expertise helped the team to resolve several difficult challenges along the way, that otherwise, would have resulted in a less-than-ideal compromise.

That's why I'm thrilled that [Ken Irwin](https://kenirwin.net/) will be the Technical Lead for the ALAO 2021, Website Working Group 🎉

# Tools & Services  
There are many all-inclusive virtual conference platforms that have sprouted up over the previous year or so ([hopin](https://hopin.com/), [Remo](https://remo.co/), and [Whova](https://whova.com/) to namecheck a few that immediately come to mind). However, there are a few reasons that you might be inclined to roll-your-own assemblage of services to host a virtual conference.

**First | Minimizing Duplicate Service Costs**

If you already purchase several of the needed components to host a virtual conference, why make a redundant purchase? As an example, ALAO has a professional subscription to the association management platform - Wild Apricot. Interacting with Wild Apricot is a familiar experience for ALAO membership, and Wild Apricot has a built-in event registration features, making it an obvious choice for handling conference registrations and payment options.

**Second | Building Capacity and Encouraging Participation**

Building your organization's overall technical capacity can encourage the expansion of services and opportunities made available to membership. While hard skills take time to develop, knowledge sharing and mentorship of colleagues are immediate, and lasting, benefits for the entire organization. Strengthening the sense of internal community can encourage members to take risks, become leaders, and pursue open positions as they become available.

**Third | Offset Contractual Losses**

If your organization has a multi-year contract with a venue to hold the annual conference, and COVID-19 requires the cancellation of any face-to-face events for the year, you may still be contractually-obligated to pay a hefty cancellation fee. To minimize organizational losses, "Doing it on the cheap" may become the motto for the year. 

Although the underpinning of the 2020 ALAO conference website were built upon an *abandoned?* project for the 2014 GDG Devfest, i.e. [Project Zeppelin](https://github.com/gdg-x/zeppelin), designing a virtual conference requires a careful selection of technologies and hosted services to be properly configured and skillfully aligned in a parallel direction. When you organization's membership very clearly sees the annual conference as the value of - and primary reason for renewing - their membership, doing it on your own is not a decision to take lightly.

### Tools
One of the key considerations in making the decision to take the DIY approach is whether or not your organization has someone willing and - perhaps most importantly - able to take the lead for the project. The project lead will need to allocate considerable volunteer time, have solid communication and project management fundamentals, and posses an intermediate set of technical skills. Below is a list of the development tools and technologies that were required to develop the 2020 ALAO Conference. [[source code](https://github.com/alaoweb/2020.alaoweb.org)]

|     |     |
| --- | --- |
| [Jekyll](https://jekyllrb.com/) | Static Site Generator |
| [SCSS](https://sass-lang.com/documentation/syntax) | CSS Pre-processer|
| [Bundler](https://bundler.io/) | Gem Dependency Management |
| [Liquid](https://shopify.github.io/liquid/) | Templating Language |
| [YAML](https://yaml.org/) | Data Serialization Standard |
| [Bootstrap](https://getbootstrap.com/) | Front-End Frameworks |
| [Ruby](https://www.ruby-lang.org/en/) | Programming Language |
| [Ruby Gems](https://rubygems.org/) | Ruby Packages (Applications or Libraries) |
| [ImageOptum](https://github.com/ImageOptim/ImageOptim) | Lossless Image Optimization |
| [Markdown](https://www.markdownguide.org/) | Plain-Text Markup Language |
| [JSON](https://www.json.org/json-en.html) |Data Interchange Format |
| [Git](https://git-scm.com/) | Software Version Control |

Of course, there are a number of others (i.e. JavaScript, jQuery) peppered in here and there, but the above is a list of the major components.

### Services
Below is a best effort to list the services that were used to create the 2020 ALAO Conference. Each listed component contains a brief description of how it was used during the conference.

[Zoom](https://zoom.us)  
Because of its overall familiarity to Ohio's higher education community, and much-less-so based upon the merits of its feature set and functionality, a decision was made to use Zoom as our streaming platform for the conference.

Prior to this decision, the Academic Library Association of Ohio (ALAO) already maintained an annual subscription to Zoom. This subscription was used to facilitate monthly board meetings and for one-off use by ALAO's many interest groups. Because there wasn't a need for additional capacity for the organization as a whole, the Website Working Group elected to purchase a separate, temporary, month-to-month subscription to Zoom, which was used exclusively for conference events. Our temporary subscription included two host licenses and two large meeting add-ons, as we anticipated 100+ attendees at the opening keynote, closing keynote, and annual awards ceremony. While we ultimately purchased the temporary subscription for two months, we could have easily reduced the duration to a single month.

Zoom was used for all real-time events, including the pre-conference workshop, trivia night, awards, and the opening and closing keynotes. As these real-time sessions were critical components of a successful conference - and we were dependent upon our notoriously unreliable home wifi connections (i.e. those pandemic work-from-home scenarios) - the two Zoom licenses were used in a host/alternative-host model. That way, if the meeting host's cat disconnected the internet connection in the middle of a keynote, the meeting would seamlessly transition over to the alternative host without noticeable disruption to the conference attendees.

Zoom was also used to host all live question and answer sessions that followed each pre-recorded conference talk. The host/alternative-host model was not used for Q&A sessions because each hour block contained two conference talks, each with its own Q&A session that required the use of a Zoom license to host. Of course, almost as soon as the conference was finished up, Zoom announced a new feature that would allow meeting attendees to self-select a breakout room of their own choosing to join. This new feature allows for more small group discussions, like our Q&A sessions, to be facilitated by fewer Zoom licenses.

[Mailchimp](https://mailchimp.com/)  
Mailchimp was used to collect email addresses to add to ALAO's mailing list. Mailchimp integration was simple, clean, and provided a vastly superior sign-up experience in comparison to the sign-up process for ALAO's mailing list via Google Groups. The free tier subscription allowed for a single audience with up to 2,000 contacts. More than enough to support the expected number of sign-ups that we'd receive at the annual conference.

[UpTimeRobot](https://uptimerobot.com/)  
Once the conference website was made available to the public, the Website Working Group needed to ensure that the site was available at all times. To alert us of any networking issues, we elected to use the free subscription tier of the website monitoring and notification service - UpTimeRobot.

Using UpTimeRobot, we were able to monitor the production and staging environments during the entire development process. Notifications were handled in several ways. First, we built a [public dashboard](https://status.alaoweb.org/) to display the status of ALAO's web properties. Although the dashboard is more of an end user tool - as there is a self-service value in answering the question, "Am I the only one having an issue?" - the dashboard also collects evidence of historical anomalies that can be used for troubleshooting purposes. Second, we used UpTimeRobot's integration with Slack to alert the Website Working Group of any critical events. These notifications turned out to be very useful when Netlify experienced routing issues, as we were able to immediately contact Netlify support to investigate.

One caveat with using the free tier of UpTimeRobot with Netlify deployments, it's not possible to define custom service statuses based upon the HTTP response of a server. After Netlify's password-protection was enabled for the conference website, to restrict access to the conference content to only registered conference attendees, this became a monitoring issue for the production site. Netlify returns a HTTP 401 Unauthorized message when password-protection is enabled and basic authentication is unsuccessful. Since password-protection was enabled for the entire conference site, and UpTimeRobot does not provide a useful method for sending authentication credentials to Netlify in a way that Netlify expects, UpTimeRobot reported the conference site as DOWN for the entire duration that password-protection was enabled. To avoid this next year, exploring the use of a Netlify configuration file, i.e. `netlify.toml`, to [selectively apply password-protection](https://docs.netlify.com/routing/headers/#syntax-for-the-headers-file) using HTTP headers is advised. Selectively applying password-protection to areas of the conference site with limited-access content will allow an HTTP 200 status to be returned to UpTimeRobot; thus, accurately displaying the status of the website as UP.

[Clearlight Communications](https://clearlight.com/)  
Clearlight Communications handles domain registration and DNS zone management for the Academic Library Association of Ohio. Netlify custom domains were created and external DNS was applied using CNAME records for `2020.alaoweb.org` and `2020-staging.alaoweb.org`. The GitHub repository contained a `main` branch and a `staging` branch. Pushes to the `main` branch would trigger a site build and deployment to [https://2020.alaoweb.org](https://2020.alaoweb.org), while pushes to the `staging` branch would rebuild the staging site at the above host. One Netlify feature that the Website Working Group found useful was the 'deployment preview'. Netlify creates a clickable URL to preview changes from any pull requests, so it was easy for any team member to see the proposed changes in a live environment without being required to checkout the branch locally and build the site on localhost.

[Slack](https://slack.com/)  
As stated earlier in this post, the primary method of communication and interaction among the Website Working Group was Slack, specifically the `#conference-website` channel. Indispensable was the ability to configure Slack to receive messages from other service providers, as our team made use of the [GitHub integration](https://slack.github.com/), [Netlify integration](https://docs.netlify.com/site-deploys/notifications), and [UpTimeRobot integration](https://uptimerobot.com/integrations/). Centralizing all of these messages in Slack proved valuable for keeping everyone aware of development activity, engaged in troubleshooting issues, and promptly reviewing all pull requests. 

[Disqus](https://disqus.com/)  
Disqus is a service that will host blog-style commenting functionality for any web site or online platform. As far as integration into the ALAO conference website is concerned, the main utility of Disqus was to increase engagement with the poster sessions, by providing a real-time comment and response capabilities on each poster. Although limited in its scope, there's a basic subscription tier that's free. The free tier only provides a single audience - from an analytics perspective, a trackable cohort of users - which was fine in our case, as the only intended audience was 2020 conference attendees and we did not intend to use the Disqus service for marketing purposes. For `.edu` sites and non-profits organizations, Disqus advertising on the free subscription tier is optional; otherwise, it's required.

[Google Forms](https://www.google.com/forms)  
The venerable Google Forms was used to collect attendee feedback for each pre-recorded session, as well as obtain survey responses for each of the keynotes, the preconference workshops, and any post-conference reflections.

As Google's suite of productivity applications and services (i.e. G Suite) is well-known in Ohio's higher education community, I'll only highlight one feature of note. Google Forms has the ability to pre-fill fields. Using the form's link, it's possible to pass a value into a form field by using a URL parameter. Because we were using Jekyll and Liquid templating, we took advantage of this feature of Google Forms to pre-populate the session title in each of the surveys. 

One advantage of this method is that it reduces the annoyance of requiring conference attendees to select a session from a long list of conference sessions before responding to any questions. Other benefits of populating the session title include: minimizing the likelihood of human error, increasing the response rate by simplifying the submission process, and providing an overall improved sense of trust in the collected data. 

Below is a snippet from the site's session modal that builds the `href` attribute for the Google Form by extracting variables and encoding the `session.title` and appending it to the `site.sessionFeedbackParameter`. When a user clicks on the survey button, the session title is pre-filled with the value of `session.title`.

```
{% if session.subtype == 'session' and site.sessionFeedbackForm != null %}
<div class="row survey-row">
    <div class="col-md-4"></div>
    <div class="col-md-8">
        <a href="{{ site.sessionFeedbackForm }}&{{ site.sessionFeedbackParameter }}={{ session.title | url_encode }}"
            class="survey-button btn"
            aria-label="Complete the survey for {{ session.title }}}">{{session.subtype | capitalize }}
            Feedback
        </a>
    </div>
</div>
{% endif %}
```

In the site's main configuration file, i.e. `config.yml`, key:value pairs are used to assign the Google Form URL to `sessionFeedbackForm` and the parameter name of the form's session title field to `sessionFeedbackParameter`.

```
sessionFeedbackForm:
sessionFeedbackParameter: "entry.1153076421"
```

This solution worked perfectly for us.

[Github](https://github.com/)  
Microsoft-owned GitHub is a hosted software development platform built on top of Git, a distributed version-control system for tracking changes in source code during the development process. The Website Working Group made extensive use of GitHub's features, including: (1) the use of GitHub Teams to manage repository permissions, (2) issue creation for feature enhancement, bug fixes, and the assignment of responsibilities, and (3) to set our meeting agendas with the built-in wiki functionality. Overall, project management was handled almost exclusively through Github’s native tool set.

[YouTube](https://www.youtube.com)  
YouTube was used to stream all pre-recorded content for the conference.

YouTube's built-in studio tools automated the process of creating an initial set video captions for human review and editing, reducing the workload for our contributors and speeding up the process to reach a finished product. Ideally, all videos would be uploaded using a set of shared standards. However, we opted to make the process simple for our contributors. We relied on YouTube's desire for consuming video content. Any video file that could be successfully uploaded to YouTube was permitted, even if this produced some discontinuity and fluctuations in video quality.

YouTube offers there statuses for an uploaded video: public, unlisted, private. Public videos are searchable and can be viewed by anyone. Unlisted videos can be viewed by anyone with a link to the video. Private videos must be selectively shared with individuals to be viewed. All conference videos were set as unlisted. This allowed the conference videos to reside on our YouTube account, but undiscoverable to a wider audience, while affording the Website Working Group the ability to write the video identifier directly into our source code. Each session modal contained an embedded YouTube player to watch the pre-recorded session video.

[Netlify](https://www.netlify.com/)  
Production and staging deployments of the 2020 conference website were handled by Netlify. While it would have been possible to use GitHub Pages for the site - in fact, early builds were hosted on GitHub Pages - Netlify provided several advantages for our team. While both could handle automated builds directly from push events to our GitHub repository, only Netlify offered site previews for every push. Preview notifications were sent to our Slack channel as a clickable URL, allowing anyone on the team to view the proposed code changes. This encouraged rapid feedback from less technical members of the Website Working Group and encouraged participation throughout the entire development process.

As the project code was released under an MIT license, ALAO was able to petition Netlify to sponsor us as an [open source project](https://www.netlify.com/legal/open-source-policy/). Netlify's generous support allowed us to use features within their Pro tier without any additional costs to the organization. We used: (1) Basic authentication to password-protect the site, allowing us to restrict access to only registered conference attendees, (2) Slack deployment notifications, and (3) granted everyone on the team access to our Netlify account, excellent for instant rollbacks to any previous version of the site, in the event of a problematic deployment. Open source sponsorship also granted 400GB/month bandwidth and 1000 build minutes/month, more resources than we would need to host a successful conference.

# In Closing

We had a lot of fun with our [code releases](https://github.com/alaoweb/2020.alaoweb.org/releases), as our guidelines for release names shows.

> Release names will follow an alphabetical nomenclature, similar to the World Meteorological Organization's naming conventions for tropical cyclones. Rather than using gendered names like the WMO, each ALAO release will be named after a spice or herb. The first alpha release being 'Anise', representing the letter 'A'. If there are more releases in a given year than there are letters in the Latin alphabet, release names should cycle back to the beginning of the Latin alphabet, doubling the letter for the release name (i.e. AA), and follow the rhythmic naming conventions of Ubuntu releases (e.g. 'Athenian Anise').

I released v1.0.2 of the site on October 17th, 2020; named, **Dandelion**. And with that, my time was up. Let the seeds fall where they may.

![Blowing a dandelion](https://media.giphy.com/media/2HOMy2lC2YoN2/source.gif)

