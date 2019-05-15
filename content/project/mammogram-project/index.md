---
title: Automatic Characterization of Breast Masses using NSGA-II based Feature Selection
summary: Propose a new feature extraction and selection method using NSGA-II for classifying masses as benign or malignant.
tags:
- machine learning
- medical image analysis
- artificial neural networks
- svm
- computer vision
- optimization

date: "2015-10-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Preprocessing of detected mass in mammogram
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: "https://bitbucket.org/masscharacterization/feature-selection/src/master/"
url_pdf: "https://github.com/trane293/trane293.github.io/blob/master/assets/projects/MassClassification.pdf"
#url_slides: "https://docs.google.com/presentation/d/1yU2VexJvZArydv7uCyEJPfAUQ0V0n8glGWEByNfmbJE/edit#slide=id.g36cafe990e_0_61"
#url_video: "https://www.youtube.com/watch?v=tlNHA7d1aLA"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Masses are one of the important yet challenging signs of breast cancer, visible in the mammogram. The paper presents a novel mass classification scheme via the introduction of new feature selection algorithm along with feature extraction technique. To capture complete and complex shape, we propose Translation, Rotation, and Shift (TRS) invariant Zernike moments as global shape descriptor. The extracted features are further clubbed with texture information. The discriminating features are then selected with a new wrapper-based feature selection scheme combined with multi-objective Non-dominated Sorting Genetic Algorithm (NSGA-II) where three objectives are optimized simultaneously. The experiments show that the proposed three objective functions allow the NSGAII to reduce the feature dimensionality from 312 to four, while significantly outperforming classifiers trained on features with high dimensionality. With a set of four features, the method achieves the best area under the receiver characteristic curve of 0.95 and an accuracy of 89.89% using an artificial neural network for 270 randomly selected images from the DDSM database.
