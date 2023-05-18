---
title: "Deep Transfer Learning-Based Musculoskeletal Abnormality Detection"
authors:
- admin
- Md Al Mehedi Hasan
- Jungpil Shin
date: "2021-05-18T00:00:00Z"
doi: "https://doi.org/10.1007/978-981-16-0586-4_16"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: "Algorithms for Intelligent Systems book series (AIS)"
publication_short: "Springer"

abstract: When the movement or musculoskeletal system (i.e., muscles, ligaments, nerves, etc.) of the human body is disrupted or affected through injury, it is called musculoskeletal disorders or MSDs. As the diagnosis of musculoskeletal conditions is complicated, detecting abnormalities from radiographs can be very significant in medical image analysis. Various computational methods have been introduced for this task which provided good classification accuracy. In this paper, we utilized the transfer learning approach to detect abnormalities because of its ability to share knowledge from similar tasks. We used an updated version of a pre-trained model (DenseNet169) to detect abnormalities for five different organs of the upper extremity. We applied data augmentation, resizing, and cropping for data preprocessing. We also tuned a couple of hyperparameters to improve our model’s performance. For evaluation, we calculated some well-known metrics to verify our model’s performance. We also compared our model’s performance with previous classifiers and found promising results. For one of the study types (finger), our classifier’s performance is improved by 67.05%. This proved that our model has the potential to be a useful tool for abnormality detection from radiographic images.

# Summary. An optional shortened abstract.
summary: We used an updated version of a pre-trained model (DenseNet169) to detect abnormalities for five different organs of the upper extremity.

tags:
- Transfer Learning, Medical Imaging
featured: false

# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/zahidemon/Musculoskeletal_Abnormality_Detection'
url_dataset: 'https://stanfordmlgroup.github.io/competitions/mura/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
