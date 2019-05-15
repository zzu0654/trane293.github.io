---
title: "Missing MRI Pulse Sequence Synthesis using Multi-Modal Generative Adversarial Network"
authors:
- Anmol Sharma
- Ghassan Hamarneh
date: "2019-04-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Missing MRI Pulse Sequence Synthesis using Multi-Modal Generative Adversarial Network"
publication_short: "MM-GAN"

abstract: Magnetic resonance imaging (MRI) is being increasingly utilized to assess, diagnose, and plan treatment for a variety of diseases. The ability to visualize tissue in varied contrasts in the form of MR pulse sequences in a single scan provides valuable insights to physicians, as well as enabling automated systems performing downstream analysis. However many issues like prohibitive scan time, image corruption, different acquisition protocols, or allergies to certain contrast materials may hinder the process of acquiring multiple sequences for a patient. This poses challenges to both physicians and automated systems since complementary information provided by the missing sequences is lost. In this paper, we propose a variant of generative adversarial network (GAN) capable of leveraging redundant information contained within multiple available sequences in order to generate one or more missing sequences for a patient scan. The proposed network is designed as a multi-input, multi-output network which combines information from all the available pulse sequences, implicitly infers which sequences are missing, and synthesizes the missing ones in a single forward pass. We demonstrate and validate our method on two brain MRI datasets each with four sequences, and show the applicability of the proposed method in simultaneously synthesizing all missing sequences in any possible scenario where either one, two, or three of the four sequences may be missing. We compare our approach with competing unimodal and multi-modal methods, and show that we outperform both quantitatively and qualitatively.
# Summary. An optional shortened abstract.
summary:
tags:
- mri
- deep learning
- generative adversarial networks
- medical image analysis
- computer vision

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/1904.12200
url_pdf: https://arxiv.org/pdf/1904.12200.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1wdWKOEI8njmkpeMgdhgkTD4hr8StOH1yP3DHgTk-SaI/edit#slide=id.g742e3e7cd_1_16'
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'MM-GAN'
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
