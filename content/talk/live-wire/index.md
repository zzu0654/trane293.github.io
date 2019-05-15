---
title: "[Paper Presentation] Interactive Live-Wire Boundary Extraction"
event: CMPT 880 Medical Imaging Meets Machine Learning
event_url: "http://www.sfu.ca/outlines.html?2018/fall/cmpt/880/g100"
location: Burnaby, BC Canada
summary: Paper presentation for the famous Live-Wire segmentation method, that was famously used in Adobe Photoshop.
abstract: "Barrett et al. propose a graph-based boundary extraction algorithm called Interactive Live-Wire, which is an extension to the original live-wire  algorithm presented in Mortensen et al. The algorithm is built upon a reformulation of the segmentation approach into graphs, particularly, an image $I$ is converted to an undirected graph with edges from a pixel $p$ to all it's neighbouring 8-connected pixels. Each pixel or node is assigned a local cost according to a function (described later). The segmentation task then becomes a problem where there needs to be a shortest path from a pixel $p$ (seed) to another pixel $q$ (free goal point), where the cumulative cost of path is minimum."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-10-10T15:00:00Z"
date_end: #"2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: #"2017-01-01T00:00:00Z"

authors: [Anmol Sharma]
tags: [linear algebra, optimization, mri, medical image analysis, computer vision]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Live-Wire in action in a mammogram'
  focal_point: Center

links:
#- icon: twitter
# icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
url_slides: "https://github.com/trane293/trane293.github.io/blob/master/assets/presentations/CMPT_880___Presentation_live_wire.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- cmpt-880

# Enable math on this page?
math: true
---

<!-- {{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's [*Slides*](https://sourcethemes.com/academic/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code. -->
