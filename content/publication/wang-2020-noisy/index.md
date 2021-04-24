---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Noisy-LSTM: Improving Temporal Awareness for Video Semantic Segmentation'
subtitle: ''
summary: ''
authors:
- Bowen Wang
- Liangzhi Li
- Yuta Nakashima
- Ryo Kawasaki
- Hajime Nagahara
- Yasushi Yagi
tags: []
categories: []
date: '2021-03-22'
lastmod: 2021-03-22T09:56:40+09:00
featured: false
draft: false

doi: ""
url_pdf: "paper/wang-2020-noisy.pdf"
url_code: "https://github.com/wbw520/NoisyLSTM"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-03-22T00:56:39.378318Z'
publication_types:
- 2
abstract: 'Semantic video segmentation is a key challenge for various applications. This paper presents a new model named Noisy-LSTM, which is trainable in an end-to-end manner, with convolutional LSTMs (ConvLSTMs) to leverage the temporal coherency in video frames. We also present a simple yet effective training strategy, which replaces a frame in video sequence with noises. This strategy spoils the temporal coherency in video frames during training and thus makes the temporal links in ConvLSTMs unreliable, which may consequently improve feature extraction from video frames, as well as serve as a regularizer to avoid overfitting, without requiring extra data annotation or computational costs. Experimental results demonstrate that the proposed model can achieve state-of-the-art performances in both the CityScapes and EndoVis2018 datasets.'
publication: 'IEEE Access'
---
