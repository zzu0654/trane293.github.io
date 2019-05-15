---
title: "A CADe System for Gliomas in Brain MRI using Convolutional Neural Networks"
authors:
- Subhasis Banerjee
- Sushmita Mitra
- Anmol Sharma
- B. Uma Shankar
date: "2018-06-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-06-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "A CADe System for Gliomas in Brain MRI using Convolutional Neural Networks"
publication_short: "CADe"

abstract: Inspired by the success of Convolutional Neural Networks (CNN), we develop a novel Computer Aided Detection (CADe) system using CNN for Glioblastoma Multiforme (GBM) detection and segmentation from multi channel MRI data. A two-stage approach first identifies the presence of GBM. This is followed by a GBM localization in each "abnormal" MR slice. As part of the CADe system, two CNN architectures viz. Classification CNN (C-CNN) and Detection CNN (D-CNN) are employed. The CADe system considers MRI data consisting of four sequences (T1, T1c, T2, and T2FLAIR) as input, and automatically generates the bounding boxes encompassing the tumor regions in each slice which is deemed abnormal. Experimental results demonstrate that the proposed CADe system, when used as a preliminary step before segmentation, can allow improved delineation of tumor region while reducing false positives arising in normal areas of the brain. The GrowCut method, employed for tumor segmentation, typically requires a foreground and background seed region for initialization. Here the algorithm is initialized with seeds automatically generated from the output of the proposed CADe system, thereby resulting in improved performance as compared to that using random seeds.
# Summary. An optional shortened abstract.
summary:
tags:
- mri
- deep learning
- convolutional neural networks
- medical image analysis
- computer vision

featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1806.07589
url_pdf: https://arxiv.org/pdf/1806.07589.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: 'https://docs.google.com/presentation/d/1wdWKOEI8njmkpeMgdhgkTD4hr8StOH1yP3DHgTk-SaI/edit#slide=id.g742e3e7cd_1_16'
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'CADe'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- missing-sequences

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
