---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'SCOUTER: Slot Attention-based Classifier for Explainable Image Recognition'
subtitle: ''
summary: ''
authors:
- Liangzhi Li
- Bowen Wang
- Manisha Verma
- Yuta Nakashima
- Ryo Kawasaki
- Hajime Nagahara
tags: []
categories: []
date: '2021-07-27'
lastmod: 2021-07-27T12:52:54+09:00
featured: true
draft: false

doi: ""
url_pdf: "paper/li-2021-scouter.pdf"
url_code: "https://github.com/wbw520/scouter"
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
  focal_point: 'right'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-07-27T03:52:53.928825Z'
publication_types:
- 1
abstract: "Explainable artificial intelligence has been gaining attention in the past few years. However, most existing methods are based on gradients or intermediate features, which are not directly involved in the decision-making process of the classifier. In this paper, we propose a slot attention-based classifier called SCOUTER for transparent yet accurate classification. Two major differences from other attention-based methods include: (a) SCOUTER's explanation is involved in the final confidence for each category, offering more intuitive interpretation, and (b) all the categories have their corresponding positive or negative explanation, which tells \"why the image is of a certain category\" or \"why the image is not of a certain category.\" We design a new loss tailored for SCOUTER that controls the model's behavior to switch between positive and negative explanations, as well as the size of explanatory regions. Experimental results show that SCOUTER can give better visual explanations while keeping good accuracy on small and medium-sized datasets."
publication: 'IEEE/CVF International Conference on Computer Vision (ICCV)'
---
