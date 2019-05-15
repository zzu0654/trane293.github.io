---
title: Predicting Survival Time for Patients Diagnosed with Gliomas Using Compressed Representation of Brain MRI Scans
summary: Convolutional neural networks based autoencoders for generating low-dimensional representations of brain MRI scans.
tags:
- deep learning
- medical image analysis
- convolutional neural network
- computer vision

date: "2017-12-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Encoder-Decoder architecture of CNN
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: "https://bitbucket.org/bcardoen/unlearning/src/master/"
url_pdf: "https://github.com/trane293/trane293.github.io/blob/master/assets/projects/cmpt_726_final_project_report.pdf"
#url_slides: "https://docs.google.com/presentation/d/1yU2VexJvZArydv7uCyEJPfAUQ0V0n8glGWEByNfmbJE/edit#slide=id.g36cafe990e_0_61"
#url_video: "https://www.youtube.com/watch?v=tlNHA7d1aLA"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In this paper we investigate the problem of predicting survival time (in days) for patients diagnosed with high grade gliomas (gliobastoma multiforme) using their
brain MRI studies. To approach this problem, we first reduce the input features into a compressed representation, learned using an unsupervised 3D convolutional neural network based autoencoder which is trained to predict its own input. Once the most informative features are learned, they are further reduced in dimensionality using singular value decomposition. We then try a number of regression based machine learning methods on this reduced data. We observe the best mean
squared error (MSE) of 125048 using K-nearest neighbours. Our observed results in terms of MSE are close to the state of the art methods as of writing this paper.
However given the regressors’ correlation results and domain knowledge, we conclude that using brain MRI data alone in this framework is insufficient to produce
predictions with high correlation.
