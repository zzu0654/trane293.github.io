---
title: "Select, Attend, and Transfer: Light, Learnable Skip Connections"
authors:
- Saeid Asgari Taghanaki
- Aicha Bentaieb
- Anmol Sharma
- S. Kevin Zhou
- Yefeng Zheng
- Bogdan Georgescu
- Puneet Sharma
- Sasa Grbic
- Zhoubing Xu
- Dorin Comaniciu
- Ghassan Hamarneh
date: "2018-04-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Select, Attend, and Transfer: Light, Learnable Skip Connections"
publication_short: "SAT Gates"

abstract: Skip connections in deep networks have improved both segmentation and classification performance by facilitating the training of deeper network architectures, and reducing the risks for vanishing gradients. They equip encoder-decoder-like networks with richer feature representations, but at the cost of higher memory usage, computation, and possibly resulting in transferring non-discriminative feature maps. In this paper, we focus on improving skip connections used in segmentation networks (e.g., U-Net, V-Net, and The One Hundred Layers Tiramisu (DensNet) architectures). We propose light, learnable skip connections which learn to first select the most discriminative channels and then attend to the most discriminative regions of the selected feature maps. The output of the proposed skip connections is a unique feature map which not only reduces the memory usage and network parameters to a high extent, but also improves segmentation accuracy. We evaluate the proposed method on three different 2D and volumetric datasets and demonstrate that the proposed light, learnable skip connections can outperform the traditional heavy skip connections in terms of segmentation accuracy, memory usage, and number of network parameters.
# Summary. An optional shortened abstract.
summary:
tags:
- convolutional neural networks
- deep learning
- medical image analysis
- computer vision

featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1804.05181
url_pdf: https://arxiv.org/pdf/1804.05181.pdf
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
  caption: 'SAT Gates'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- collaboration

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
