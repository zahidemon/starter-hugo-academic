---
title: 'A Mixed Convolutional Neural Network for Pre-miRNA Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Md Al Mehedi Hasan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-12-26T00:00:00Z'
doi: 'https://doi.org/10.1109/ICECTE48615.2019.9303537'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-12-26T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2019 3rd International Conference on Electrical, Computer & Telecommunication Engineering 
publication_short: In ICECTE 2019

abstract: The biogenesis of miRNA is divided into two types based upon their different pathways. One of them is known as the canonical pathway and the other one is the mirtron pathway. This pathway depends on splicing rather than any enzyme. As the mirtron pathway is recently discovered, their identification is quite challenging due to less number of annotations. So the identification of mirtrons can be quite productive in understanding their functionality. Several machine learning algorithms have been introduced over the years based mostly upon calculated feature selection which produced good classification performance. We have also seen that neural networks like convolutional neural networks (CNN) applied on modified nucleotide sequences have given better performance. In this paper, we introduced an improved mixed convolutional neural network with multiple different sized filters and max-pooling layers using binary "one-hot" encoding and padding. We also used k-fold cross-validation and grid search to choose the values of hyperparameters. As we know neural networks tend to extract features automatically, our model did the same in the convolution and max-pooling layers. We evaluated our model in an independent test set and the results were quite satisfactory. We think our model can be used to predict mirtrons from nucleotide sequences. Even though we tried our best to fine-tune our model, we believe there's still room for improvement as CNN involves tuning of a number of hyperparameters.

# Summary. An optional shortened abstract.
summary: In this paper, we introduced an improved mixed convolutional neural network with multiple different sized filters and max-pooling layers using binary "one-hot" encoding and padding for pre-miRNA classification

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9303537'
url_code: 'https://github.com/zahidemon/Pre-miRNA-Classification'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1VDDYx-KpWS71xvxNQMlGOuY7AtREBRCg/edit?usp=sharing&ouid=112432914184650588612&rtpof=true&sd=true'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
