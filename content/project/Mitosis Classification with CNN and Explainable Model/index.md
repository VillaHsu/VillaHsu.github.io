---
title: Mitosis Classification with CNN and Explainable Model
summary: Using deep learning to classify Mitosis stage.
tags:
- Deep Learning
date: "2019-06-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/stevengogogo/MitosisClassification
- name: Slide
  url: https://docs.google.com/presentation/d/1ehAQE3JU7z6V9cX56RJXGWztyd_5NdBW/edit?usp=sharing&ouid=115922715586840460448&rtpof=true&sd=true
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This project used convolutional neural network to classify mitotic stages via microscopic imaging. Noted that the classification is based on either nucleus or mitochondrial morphology to obtain time series classification. After CNN was trained, we applied LIME and SHAP algorithm to investigate the attention of the trained neural network. This is a pipeline to implement reliable classification algorithm with cell images.
