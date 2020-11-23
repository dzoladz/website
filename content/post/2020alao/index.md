+++
date = "2020-10-28T11:00:00"
draft = true
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

One upside of 2020 has been the expansion of learning opportunities that have become real opportunities, as library and library-adjacent conference and workshops transition to an online delivery. I've registered for three times as many conference as I would in a normal year, but I've also not attended just as many of those events because I've has other work that I found more interesting to pursue. I guess that's a consequence of free registration - although I'm not sure how it's been possible for these events to have no associated fees to attend, when putting on a conference of any size has tangible costs associated with it.  Anyway... that's all a divergence from the intent of this post, which is to reflect upon my work for the [2020 ALAO Conference](https://2020.alaoweb.org/)

Another upside to 2020 has been the number of opportunities to put the spectrum of my technical abilities into practice, as the great learning continues to bloom.

Serving as the Chair of the Website Working Group and Technical Lead for the Academic Library Association of Ohio (ALAO) annual conference - ALAO's first ever fully online conference - has been a highlight of my 2020. While unexpected, it was a wonderful opportunity to:

- [1] expand the technical capacity of ALAO
- [2] establish a GitHub organization to warehouse and share useful scripts and application code between ALAO members
- [3] obtain a non-profit Slack account with additional features and limits for use by the organization
- and, [4] apply for an open source project account with Netlify to host application deployments for the 2020 conference website.

Volunteer projects like this one always provide an opportunity to exercise and develop my leadership abilities, mentor younger colleagues, and further solidify my project management abilities.

### Team
The 2020 ALAO Conference website was themed, customized, enhanced, and maintained by the Website Working Group. Members of the 2020 Website Working Group are as follows:

- David Green (State Library of Ohio)
- Melissa Hill (Ohio Wesleyan University)
- Ken Irwin (Miami University)
- Ryan Scott (Columbus State Community College)
- Zach Walton (The Ohio State University)

Our primary method of communication was the `#conference-website` channel of the ALAO Slack workspace. Project management was mainly facilitated through Github’s native tooling, via issue creation, issue assignment of responsibilities, and a wiki for setting each meeting's agenda.

Our team worked in 3 week sprints over the course of a few months to bring the conference site online. Each sprint would begin with an hour-long meeting to review our progress, discuss any open issues, and set goals and priorities for the next sprint. Since our team was a combination of experienced developers and some folks who were entirely new to static site generators and source code versioning tools, the 3 week pace worked out well for the whole team. It provided enough cushion to begin an exploration of the code, generate questions, and pursue self-guided learning to get up-to-speed, while keeping enough momentum under the project for the more experiences team members to not lose interest and continue to drive the project forward. As a hands-on mentorship opportunity, the hard skills acquired during the buildout of the conference website are easily transferable onto digital projects at each team member's local institution.

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

Ken Irwin from Miami University will be the Technical Lead for the ALAO 2021, Website Working Group.

# Tools & Services  
There are many all-inclusive virtual conference platforms that have sprouted up over the previous year or so ([hopin](https://hopin.com/), [Remo](https://remo.co/), and [Whova](https://whova.com/) immediately come to mind). However, there are a few reasons that you might be inclined to roll-your-own assemblage of services to host a virtual conference.

First: If you already purchase several of the needed components to host a virtual conference. As an example, ALAO has a professional subscription to the association management platform - Wild Apricot. Interacting with Wild Apricot is a familiar experience for ALAO membership, and Wild Apricot has a built-in event registration features, making it an obvious choice for handling conference registrations and payment.

Second: Building your organization's overall technical capacity can encourage the expansion of services and opportunities made available to membership. While hard skills take time to develop, knowledge sharing and mentorship of colleagues are immediate benefit. Strengthening the organizations sense of internal community can encourage members to take on leadership roles as they become available.

Third: If your organization has a multi-year contract with a venue to hold the annual conference, and COVID-19 requires the cancellation of any face-to-face events for the year, you may still be contractually-obligated to pay a hefty cancellation fee. To minimize organizational losses, "Doing it on the cheap" may become the motto for the year. 

Although the underpinning of our conference website are built upon an (abandoned?) projected for the 2014 GDG Devfest called [Project Zeppelin](https://github.com/gdg-x/zeppelin), designing a virtual conference requires a careful selection of technologies and hosted services to be properly aligned and smoothly working in a parallel direction. When you organization's membership very clearly sees the annual conference the value of - and primary reason for renewing - their membership, doing it on your own is not a decision to take lightly.

### Tools
One of the key considerations in making a decision to take the DIY approach is whether or not you have someone willing and - perhaps most importantly - able to take the lead for the project. The project lead will need to allocate considerable volunteer time, possess solid project management fundamentals, and have an intermediate set of technical skills. Below is a list of the development tools and technologies that were required to develop the 2020 ALAO Conference - ALAO's first fully online conference. [[source code](https://github.com/alaoweb/2020.alaoweb.org)]

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
Below is an effort to list many of the services that were  used to create the 2020 ALAO Conference - ALAO's first fully online conference. Each listed component contained a brief description of how it was used during the conference.

[Zoom](https://zoom.us)  
Because of its overall familiarity within Ohio's higher education communities, and less so based upon the merits of its feature set and functions, a decision was made to use Zoom as our streaming platform for the conference.

The Academic Library Association of Ohio (ALAO) maintains an annual subscription to Zoom to facilitate monthly board meetings and also for use by ALAO's many interest groups. Because there wasn't a need for additional capacity for the organization as a whole, the Website Working Group elected to purchase a separate, temporary, month-to-month subscription to Zoom to use exclusively for conference events. Our temporary subscription included two host licenses and two large meeting add-ons, as we anticipated 100+ attendees at the opening keynote, closing keynote, and annual awards ceremony.

Zoom would be used for all real-time events, including the pre-conference workshop, trivia night, awards, and the opening and closing keynotes. As these real-time sessions were critical components of a successful conference - and we were dependent upon notoriously unreliable home wifi connections due to pandemic work-from-home scenarios - the two Zoom licenses were used in a host/alternative-host model. That way, if the meeting host's cat disconnected the internet connection in the middle of a keynote, the meeting would seamlessly transition over to the alternative host without noticeable disruption to the conference attendees.

Zoom was also used to host a live question and answer session following each pre-recorded conference talk. The host/alternative-host model was not used for Q&A sessions because each hour block contained two conference talks, each with its own Q&A session that required a Zoom license to host. Of course, almost as soon as the conference was finished up, Zoom announced a new feature that would allow meeting attendees to self-select a breakout room of their own choosing to join... allowing for more small group discussions like Q&A to be facilitated by fewer Zoom licenses.

[Mailchimp](https://mailchimp.com/)  
Mailchimp was using to collect email addresses to add to ALAO's mailing list. Mailchimp integration was simple, clean, and provided a vastly superior sign-up experience compared to the sign-up process for ALAO's mailing list via Google Groups. The free tier subscription allowed for a single audience with up to 2,000 contacts. More than enough to support the annual conference.

[UpTimeRobot](https://uptimerobot.com/)  
Once the conference website was made available to the public, the Website Working Group needed to ensure that the site was available at all times. UpTimeRobot is a website monitoring service with a free subscription tier that met our needs.

Using UpTimeRobot, we were able to monitor the production and staging environments during the entire development process. Notifications were handled in several ways. First, we built a [public dashboard](https://status.alaoweb.org/) to display the status of our web properties at any given time. The dashboard is more of an end user tool, as there is a self-service value in answering the question, "Am I the only one having an issue?". Second, we using UpTimeRobot's integration will Slack to alert the Website Working Group of any critical events. These notifications turned out to be very useful when Netlify deploys experienced routing issues for about an hour on one day.

One caveat with using the free tier of UpTimeRobot, it's not possible to define custom statuses based upon the HTTP response of a server. This became an issue for monitoring the production conference site when basic authentication password-protection was enabled for the conference site to restrict content access to only registered conference attendees. Netlify returns an HTTP 401 Unauthorized message when password-protection is enabled. Since password-protection was enabled for the entire conference site, and UpTimeRobot does not provide a viable method to send credentials to Netlify in a way that Netlify expects, UpTimeRobot reported the conference site as DOWN for the entire duration of active conference. To avoid this next year, we're exploring the use of a Netlify configuration file `netlify.toml` to [selectively apply password-protection](https://docs.netlify.com/routing/headers/#syntax-for-the-headers-file) using HTTP headers, to only the areas of the conference site containing restricted content.

[Clearlight Communications](https://clearlight.com/)  
Domain registration and DNS zone management for the Academic Library Association of Ohio is handled through Clearlight Communications. External DNS was applied to Netlify custom domains by establishing CNAME records for `2020.alaoweb.org` and `2020-staging.alaoweb.org` to the relevant Netlify custom domains for sites being built from push actions to their respective branches of code from the GitHub repository. Netlify creates a 'deploy preview' for any pull requests, so it was easy for Website Working Group team members to see the proposed changes in a live environment without being required to checkout the branch locally and build the site on localhost.

[Slack](https://slack.com/)  
The primary method of communication and interaction among the Website Working Group was Slack, specifically the `#conference-website` channel. Indispensable was the ability to configure Slack to receive messages from other service providers by taking advances of the  [GitHub integration](https://slack.github.com/), [Netlify integration](https://docs.netlify.com/site-deploys/notifications), and [UpTimeRobot integration](https://uptimerobot.com/integrations/). Centralizing these messages in Slack proved valuable for keeping everyone involved in the development process, troubleshooting issues, and reviewing pull requests. 

[Disqus](https://disqus.com/)  
Disqus is a service for hosted commenting functionality for web site or other online platforms. The main function of the Disqus was to increase engagement with the poster sessions by providing real-time comment and response capabilities on each of the posters.

Although limited in its scope, there's a basic subscription tier that's free for Disqus. The free tier only provides a single audience - from an analytics perspective, a trackable cohort of users - which was fine in our case, as the only intended audience was 2020 conference attendees and we did not intend to use the Disqus service for marketing purposes. For .edu site and non-profits, Disqus advertising on the free tier is optional otherwise, it's required.

[Google Forms](https://www.google.com/forms)  
The venerable Google Forms was used to collect feedback and survey responses for each pre-recorded session, keynote, preconference workshop, and following the closing keynote, the conference as a whole. As Google's suite of productivity applications and services (i.e. G Suite) is a strong conductor to Microsoft 365 services in Ohio's higher education community, I'll only highlight one feature of note.

Google Forms has the ability to prefill form fields by using the form's link to pass a URL parameter value. Because we were using Jekyll and Liquid templating, we took advantage of this feature of Google Forms to pre-populate the session title in the feedback survey. Rather than require conference attendees to select the session - from a dropdown list of conference sessions - to provide feedback,

Reduce the likelihood of human error, increase the response rate by simplifying the submission process, and provide an improved sense of trust in the data the conference planning committee would be providing to our speakers. 

##### Session modal code:

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

##### config.yml file

```
# -------------------------------------------------------------
# Surveys
# -------------------------------------------------------------
sessionFeedbackForm:
sessionFeedbackParameter: "entry.1153076421"
```

[Github](https://github.com/)  
Microsoft-owned GitHub is a hosted software development platform built on top of Git, a distributed version-control system for tracking changes in source code during the development process. The Website Working Group made extensive use of GitHub's features, including: (1) the use of GitHub Teams to manage repository permission, (2) issue creation for enhancement tracking, bug fixes, and assignment of responsibilities, and (3) setting our meeting agendas using the built-in wiki functionality. Overall, the project management was handled almost exclusively through Github’s native tool set.

[YouTube](https://www.youtube.com)  
YouTube was used to stream all of the pre-recorded content for the conference.

All videos were uploaded with a set of shared standards. When that proved to be a bit too technical and intimidating for our presenters, we were able to really on YouTube's desire for consuming video content. Any file format that could be successfully uploaded to YouTube was permitted, even if this produced some discontinuity and divergent expectations of video quality.

YouTube's built-in tools in studio were helpful in generating automated captions and then human review and editing those files.

YouTube offers these statuses for an uploaded video: public, unlisted, private. All videos were set as unlisted. This allowed the videos to sit on our YouTube account as unsearchable, while affording us the ability to code the Video ID into our source code for the conference. Pre-recorded videos were embedded in session modals and posters... and the display of conference content was controlled via a Boolean variable in `config.yml`

[Netlify](https://www.netlify.com/)  
Production and staging deployments of the 2020 conference website were handled by Netlify. While it would have been possible to use GitHub Pages for the site - in fact, early builds were hosted on GitHub Pages - Netlify provided several advantages for our team. While both could handle automated builds directly from push events to our Git repository, Netlify offered site previews for every push. Notification of a fresh previews was sent to our Slack channel as a URL that could be clicked to view the proposed changes. This encourages rapid feedback from less technical members of the Website Working Group. These often unheard voices were welcome in steering the site, and encourages participation throughout the entire development process.

Since our project code for the website was released under an MIT license, ALAO was able to petition Netlify to sponsor us as an [open source project](https://www.netlify.com/legal/open-source-policy/). Netlify's generous support allowed us to use features within their Pro tier without any additional costs to the organization. We used: (1) Basic authentication to password-protect the site, allowing us to restrict access to only registered conference attendees, (2) Slack deploy notifications, (3) more than one team member access to the Netlify team, excellent for instant rollbacks to any previous version in the event of a problematic deploy. Open source sponsorship also granted (400GB /month bandwidth) and (1000 minutes /month build minutes), well within the resources that were would need for a successful conference.

# Releases

https://github.com/alaoweb/2020.alaoweb.org/releases

Initial Release - June 21, 2020
A snapshot of the conference site code demonstrated to the 2020 Conference Planning Committee. It represents a significant departure from the originating code base of Project Zeppelin. Although an alpha release, this version of the code is being presented outwardly to potential conference sponsors.

Release names will follow an alphabetical nomenclature, similar to the World Meteorological Organization's naming conventions for tropical cyclones. Rather than using gendered names like the WMO, each ALAO release will be named after a spice or herb. The first alpha release being 'Anise', representing the letter 'A'. If there are more releases in a given year than there are letters in the Latin alphabet, release names should cycle back to the beginning of the Latin alphabet, doubling the letter for the release name (i.e. AA), and follow the rhythmic naming conventions of Ubuntu releases (e.g. 'Athenian Anise').

