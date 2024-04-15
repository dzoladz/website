---
title: "Contactless Library Service: Case Studies from Ohio's Private Academic Libraries"
authors:
- Derek Zoladz
- Rebecca Raeske-Grinch
- Laura D'Amato
- Noreen Mulcahy

author_notes:
  - "Project Lead"
  - "Equal Contribution"
  - "Equal Contribution"
  - "Equal Contribution"

date: "2022-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-31T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["speech"]

# Publication name and optional abbreviated publication name.
publication: "ALAO Annual Conference 2022"
publication_short: ""

abstract: "While contactless library services have been available for decades, there's been a distinct shift in the design of and expectations from contactless services in the last few years. Whether accelerated by the pandemic, or by the expansion of contactless services in adjacent industries, there’s an increasing demand for simplicity and convenience of library services. A smooth user experience on the surface often involves complex behind-the-scenes procedures, requiring a depth of technical knowledge, cross-organizational communication skills, and a high level of patience and understanding as the process for creating new service models that remove barriers to accessing library resources can be burdensome."

# Summary. An optional shortened abstract.
summary: 

tags:
  - ALAO

featured: true

links:
  - name: "Slides"
    url: "/publication/contactless-library-services/assets/slides.pdf"
  - name: "Agenda"
    url: "/publication/contactless-library-services/assets/program.pdf"
  - name: "Notes"
    url: "/publication/contactless-library-services/assets/notes.pdf"
  - name: "Conference Website"
    url: "https://www.alaoweb.org/conferences/2022/program"
  - name: "Simplified Diagram"
    url: "https://dreampuf.github.io/GraphvizOnline/?url=https://gist.githubusercontent.com/dzoladz/d9d7f8f3bf5021f7e983aa7dbfcd339d/raw/9b0445998406fc5f07d8a7abfb1a64c2e7c7a813/simplified-alao2022.gv#strict%20digraph%20MobileCredentials%20%7B%0A%20%20rankdir%3DRL%0A%20%20splines%3Dortho%0A%20%20compound%3Dtrue%0A%20%20concentrate%3Dfalse%0A%20%20label%3D%22BW%20Mobile%20Credentials%22%0A%20%20node%5Bstyle%3D%22rounded%2Cfilled%2Cbold%22%2C%20shape%3Dbox%2C%20fixedsize%3Dtrue%2C%20width%3D1.6%2C%20fontname%3D%22Arial%22%5D%0A%20%20%0A%20%20%2F%2F%20SubGraphs%0A%20%20%2F%2F%20Note%3A%20cluster_%20prefix%20is%20important%0A%20%20subgraph%20cluster_baldwin_wallace%20%7B%0A%20%20%20%20label%3D%22Badlwin%20Wallace%22%0A%20%20%20%20style%3Drounded%0A%20%20%20%20bgcolor%3D%22%23fafafa%22%0A%20%20%20%20scheduler1%5Blabel%3D%22Scheduler%22%5D%0A%20%20%20%20database1%5Bshape%3Dcylinder%2C%20label%3D%22Ellucian%20ERP%22%2C%20height%3D1.5%5D%0A%20%20%20%20file1%5Bshape%3Dnote%2C%20label%3D%22TSV%22%2C%20URL%3D%22https%3A%2F%2Fopal-libraries.org%2Fpatron-loads%2Fprofiles%22%5D%0A%20%20%20%20database3%5Bshape%3Dcylinder%2C%20label%3D%22CBORD%22%2C%20height%3D1.5%5D%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20rank%3Dsame%3B%0A%20%20%20%20%20%20%20%20scheduler1%2Cdatabase1%0A%20%20%20%20%7D%0A%20%20%7D%0A%20%20%0A%20%20subgraph%20cluster_ohionet%20%7B%0A%20%20%20%20label%3D%22AWS%22%0A%20%20%20%20style%3Drounded%0A%20%20%20%20bgcolor%3D%22%23fafafa%22%0A%20%20%20%20pickup%5Blabel%3D%22%2Fbw%2Fpickup%22%2C%20shape%3Dfolder%5D%0A%20%20%20%20dropoff%5Blabel%3D%22%2Fbw%2Fdropoff%22%2C%20shape%3Dfolder%5D%0A%20%20%20%20cron%5Blabel%3D%22cron%22%5D%0A%20%20%20%20dataTransformation%5Blabel%3D%22Data%20Transformation%5CnPython%22%2C%20width%3D2%2C%20height%3D2%5D%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20rank%3Dsame%3B%0A%20%20%20%20%20%20%20%20cron%2C%20pickup%0A%20%20%20%20%7D%0A%20%20%7D%0A%20%20%0A%20%20subgraph%20cluster_sierra%20%7B%0A%20%20%20%20%20%20label%3D%22Sierra%22%0A%20%20%20%20%20%20style%3Drounded%0A%20%20%20%20%20%20bgcolor%3Dtan%0A%20%20%20%20%20%20scheduler2%5Blabel%3D%22Scheduler%22%5D%0A%20%20%20%20%20%20api1%5Blabel%3D%22API%20Server%22%5D%0A%20%20%20%20%20%20database2%5Bshape%3Dcylinder%2C%20label%3D%22Database%22%5D%0A%20%20%20%20%20%20note5%5Bstyle%3Dnone%3Bshape%3Dplaintext%3B%20label%3D%22Ingest%5Cnvia%20Load%20Table%22%2C%20width%3D1.5%5D%0A%20%20%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%20%20rank%3Dsame%3B%0A%20%20%20%20%20%20%20%20%20%20scheduler2%2Capi1%2Cdatabase2%2C%20note5%0A%20%20%20%20%20%20%7D%0A%20%20%7D%0A%20%20%0A%20%20subgraph%20cluster_patron%20%7B%0A%20%20%20%20%20%20label%3D%22Library%20Environment%22%0A%20%20%20%20%20%20style%3Drounded%0A%20%20%20%20%20%20bgcolor%3D%22%23fafafa%22%0A%20%20%20%20%20%20phone1%5Blabel%3D%22Mobile%20Code%22%2C%20width%3D2.5%5D%0A%20%20%20%20%20%20%2F%2Fnote6%5Bstyle%3Dnone%2C%20shape%3Dplaintext%2C%20label%3D%22scans%22%2C%20width%3D1%5D%0A%20%20%7D%0A%20%20%0A%20%20%2F%2F%20Free-Floating%20Nodes%0A%20%20%2F%2F%0A%20%20%2F%2Fnote2%5Bstyle%3Dnone%3Bshape%3Dplaintext%3B%20label%3D%22key-based%20SSH%22%2C%20width%3D1.5%5D%0A%20%20scanner1%5Blabel%3D%22Emitted%20Light%20Scanner%22%2C%20width%3D2.5%5D%0A%20%20scanner2%5Blabel%3D%22RFID%20Reader%22%2C%20width%3D2.5%5D%0A%20%20keycard1%5Blabel%3D%22Physical%20Building%5CnLocks%22%2C%20width%3D2%2C%20height%3D1%5D%0A%20%20%0A%20%20%2F%2F%20Dotted%20Edges%20%7C%20No%20Arrowhead%0A%20%20edge%5Barrowhead%3Dnone%2C%20style%3Ddotted%5D%0A%20%20%0A%20%20%2F%2F%20Dotted%20Edges%0A%20%20edge%5Barrowhead%3Dnormal%2C%20style%3Ddotted%5D%0A%0A%20%20%2F%2F%20Thin%20Edges%20%7C%20No%20Arrowhead%0A%20%20edge%5Barrowhead%3Dnone%2C%20width%3D1%2C%20style%3Dnone%2C%20shape%3Dplaintext%5D%0A%20%20scheduler2%20-%3E%20note5%0A%20%20%0A%20%20%2F%2F%20Blod%20Edges%0A%20%20edge%5Barrowhead%3Dnormal%2C%20style%3Dbold%5D%0A%20%20file1%20-%3E%20dropoff%20%5Blabel%3D%22Key-based%20SSH%22%2C%20minlen%3D2%5D%0A%20%20%0A%20%20%2F%2F%20Thin%20Edges%0A%20%20edge%5Barrowhead%3Dnormal%2C%20style%3Dnormal%5D%0A%20%20dropoff%20-%3E%20dataTransformation%0A%20%20dataTransformation%20-%3E%20pickup%0A%20%20pickup%20-%3E%20scheduler2%0A%20%20note5%20-%3E%20database2%0A%20%20database1%20-%3E%20file1%0A%20%20%0A%20%20%2F%2F%20Hashed%20Edges%0A%20%20edge%5Barrowhead%3Dnormal%2C%20style%3Ddashed%2C%20color%3Dred%5D%0A%20%20api1%20-%3E%20dataTransformation%20%5Bdir%3Dboth%5D%0A%20%20scanner1%20-%3E%20phone1%0A%20%20scanner1%20-%3E%20api1%20%5Blhead%3Dcluster_sierra%5D%0A%20%20scanner2%20-%3E%20api1%20%5Blhead%3Dcluster_sierra%5D%0A%20%20%0A%20%20%2F%2F%20Hashed%20Edges%20%7C%20No%20Arroehead%20(control%20lines)%0A%20%20edge%5Barrowhead%3Dnone%2C%20style%3Ddashed%2C%20penwidth%3D3%2C%20color%3Ddarkgreen%5D%0A%20%20cron%20-%3E%20dataTransformation%0A%20%20scheduler1%20-%3E%20database1%0A%7D"

url_pdf:
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
