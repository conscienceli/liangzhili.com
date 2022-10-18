---
title: One-shot pruning of gated recurrent unit neural network by sensitivity for
  time-series prediction
date: '2022-11-01'
draft: false
publishDate: '2022-11-01T02:32:51.414474Z'
authors:
- Hong Tang
- Xiangzheng Ling
- Liangzhi Li
- Liyan Xiong
- Yu Yao
- Xiaohui Huang
publication_types:
- 2
featured: false



doi: ""
url_pdf: "paper/tang-2022-one.pdf"
url_code: "https://github.com/imLingo/SCGRU"
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
abstract: 'Although deep learning models have been successfully adopted in many applications, they are facing challenges to be deployed on energy-limited devices (e.g., some mobile devices, etc.) due to their high computation complexity. In this paper, we focus on reducing the costs of Gated Recurrent Units (GRUs) for time-series prediction tasks and we propose a new pruning method that can recognize and remove the neural connections that have little influence on the network loss, using a controllable threshold on the absolute value of the pre-trained GRU weights. This is different from existing approaches which usually try to find and preserve the connections with large weight values. We further propose a sparse-connection GRU model (SCGRU) that only needs a one-time pruning (with fine-tuning), rather than using multiple prune-retrain cycles. A large number of experimental results demonstrate that the proposed method is able to largely reduce the storage and computation costs while achieving the state-of-arts performance in two datasets.'

publication: '*Neurocomputing*'
---

