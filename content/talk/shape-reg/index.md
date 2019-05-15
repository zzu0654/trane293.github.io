---
title: "[Paper Presentation] Shape Registration in Implicit Spaces Using Information Theory and Free Form Deformations"
event: CMPT 880 Medical Imaging Meets Machine Learning
event_url: "http://www.sfu.ca/outlines.html?2018/fall/cmpt/880/g100"
location: Burnaby, BC Canada
summary: This talk covers a classical method for shape registration using approaches from information theory and deformations.
abstract: "Shape registration problem have been an active research topic in computational geometry, computer vision, medical image analysis and pattern recognition communities. Also called the shape alignment, it has extensive uses in recognition, indexing, retrieval, generation and other downstream analysis of a set of shapes. There have been a variety of works that approach this problem, with the methods varying mostly in terms of (can be called pillars of registration) the shape representation, transformation and registration criteria that is used. One such method is proposed by Huang et al. in this paper, which uses a novel combination of the three pillars, where an implicit shape representation is used to register an object both globally and locally. For the registration criteria, the proposed method uses Mutual Information based criteria for its global registration phase, while sum-squared differences (SSD) for its local phase.

Following global registration, local registration is performed by embedding a control point grid using the Incremental Free Form Deformation (IFFD) method. The objective function to minimize is used as the sum squared differences (SSD). The local registration is also offset by using a multi-resolution framework, which performs deformations on control points of varying resolution, in order to account for small local deformations in the shape. In case where there is prior information available for feature point correspondence between the two shapes, this prior knowledge can be added as a plugin term in the overall local registration optimization term.

The method was applied on statistically modelling anatomical structures, 3D face scan and mesh registration. "

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-10-31T15:00:00Z"
date_end: #"2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: #"2017-01-01T00:00:00Z"

authors: [Anmol Sharma]
tags: [machine learning, shape registration, computer vision, medical image analysis]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Landmark detection in CT by RL agent'
  focal_point: Center

links:
#- icon: twitter
# icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
url_slides: "https://github.com/trane293/trane293.github.io/blob/master/assets/presentations/cmpt_880_shape_registration.pdf"
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
