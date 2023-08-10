---
title: Probabilistic approaches for Data Augmentation
summary: This is for CS6190 probabilistic machine learning project. Here, we have taken a small dataset of medical images (~230) and used two probabilistic approaches, generative adversarial networks (GAN) and variational autoencoder (VAE), to generate more realistic images to increase the number of samples, which play significant roles in deep learning-based methodologies.
tags:
  - Deep Learning
  - Generative Adversarial Network
  - Variational Autoencoder
date: '2023-04-27T00:00:00Z'

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
url_code: 'https://github.com/mahimoksha/CS6190---ProbabilisticMLProject'
url_pdf: ''
url_slides: ''
url_video: ''
url_dataset: 'https://www.kaggle.com/datasets/nafin59/monkeypox-skin-lesion-dataset'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Deep Learning is data hungry and data augmentation has proven extremely useful in improving model generalization performance in medical image analysis tasks; it is very difficult to generalize with fewer data; where in our project, we discuss whether a patient has monkeypox or not with very limited data. There are proven methods where increasing amounts of training samples are valuable for the performance of model in generalization such as organ-at-risk (OAR) segmentations. So, it is very important to provide challenging augmentation to the model to increase the data diversity. In this project, we are trying to solve a task that is to classify if the sample has monkeypox or not with very less data by analyzing with different data augmentation techniques. Our objective is to employ variational autoencoder (VAE) and generative adversarial network (GAN), to generate new samples, which will enrich the number of samples in our training strategy.

We have setup the baselines using conventional augmentation techniques and  tried to add probabilistic machine learning based methodologies GAN and VAE to generate more diversified samples. We compared the baseline augmentation methods with probabilistic approaches and compare their performance on same model architectures (ResNet34 and ResNet50). We can see significant improvements to the performance on held-out data when probabilisitc models are used for increasing the sample space. 

Image credit: (https://exemplar-vae.github.io/exemplar-vae-generation.svg)
