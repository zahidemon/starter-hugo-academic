---
title: Deep Transfer Learning-Based Musculoskeletal Abnormality Detection
summary:  We utilized the transfer learning approach to detect abnormalities because of its ability to share knowledge from similar tasks. We used an updated version of a pre-trained model (DenseNet169) to detect abnormalities for five different organs of the upper extremity.
tags:
  - Deep Learning
  - Transfer Learning
date: '2020-08-12T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: ''

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/zahid_aziz_emon
url_code: 'https://github.com/zahidemon/Musculoskeletal_Abnormality_Detection'
url_pdf: ''
url_slides: ''
url_video: ''
url_dataset: 'https://stanfordmlgroup.github.io/competitions/mura/'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

When the movement or musculoskeletal system (i.e., muscles, ligaments, nerves, etc.) of the human body is disrupted or affected through injury, it is called musculoskeletal disorders or MSDs. As the diagnosis of musculoskeletal conditions is complicated, detecting abnormalities from radiographs can be very significant in medical image analysis. Various computational methods have been introduced for this task which provided good classification accuracy. In this project, we utilized the transfer learning approach to detect abnormalities because of its ability to share knowledge from similar tasks. We used an updated version of a pre-trained model (DenseNet169) to detect abnormalities for five different organs of the upper extremity. We applied data augmentation, resizing, and cropping for data preprocessing. We also tuned a couple of hyperparameters to improve our model’s performance. For evaluation, we calculated some well-known metrics to verify our model’s performance. We also compared our model’s performance with previous classifiers and found promising results. For one of the study types (finger), our classifier’s performance is improved by 67.05%. This proved that our model has the potential to be a useful tool for abnormality detection from radiographic images.


