---
title: Evaluating Machine Translation Systems using Weighted Vote of Different Scoring Metrics
summary: We propose a novel multi-metric voting scheme for evaluating machine translation systems.
tags:
- machine learning
- deep learning
- natural language processing
- machine translation
- artificial neural networks
- svm

date: "2017-12-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Various hyperparameters used in the classifiers
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: "https://github.com/trane293/nlp-project/tree/master/evaluator"
url_pdf: "https://github.com/trane293/trane293.github.io/blob/master/assets/projects/cmpt_825_final_project_report.pdf"
#url_slides: "https://docs.google.com/presentation/d/1yU2VexJvZArydv7uCyEJPfAUQ0V0n8glGWEByNfmbJE/edit#slide=id.g36cafe990e_0_61"
#url_video: "https://www.youtube.com/watch?v=tlNHA7d1aLA"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Automatic evaluation metrics are fundamentally important for Machine Translation, allowing comparison of systems performance and efficient training. Current evaluation metrics fall into two classes: heuristic approaches, like BLEU or METEOR, and those using supervised learning trained on human judgment data. Evaluating a machine translation system using such heuristic metrics is faster, easier and cheaper as compared to human evaluations, which require trained bilingual evaluators. In this report, we present our approach to combine multiple automatic evaluation heuristics using machine learning and then compare the quality of translation of two different MT system. Our results show that while each heuristic approach can provide a valid comparison between two system, combining the techniques using our machine learning approach provides higher accuracy.
