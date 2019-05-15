---
title: Dealing with Missing Modalities in Medical Images What's Missing?
event: Medical Image Analysis Laboratory Reading Group
event_url: "http://medicalimageanalysis.com"
location: Burnaby, BC Canada
summary: A talk regarding the current state-of-art in handling missing inputs for segmentation or classification problems.
abstract: "This presentation introduces the problem of missing modalities, and draws a parallel between 'channels' in computer vision to 'modalities' or 'sequences' in medical imaging. I talk about the two fundamental ways with which robustness to missing inputs can be achieved, and present state-of-art methods for both. Specifically, I present two papers [HeMIS](https://arxiv.org/abs/1607.05194) and [MM-Synthesis](https://ieeexplore.ieee.org/abstract/document/8071026) that approach the problem in two different ways."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-07-12T13:00:00Z"
date_end: #"2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: #"2017-01-01T00:00:00Z"

authors: [Anmol Sharma]
tags: [deep learning, machine learning, mri, medical image analysis, computer vision]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'BraTS 2018 Dataset with 4 Sequences, which is used to segment tumor region'
  focal_point: Center

links:
#- icon: twitter
# icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
url_slides: "https://github.com/trane293/trane293.github.io/blob/master/assets/presentations/20180712_Anmol_Dealing_With_Missing_Modalities.pdf"
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
- missing-sequences

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
