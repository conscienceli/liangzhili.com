---
title: "IterNet: Retinal Image Segmentation Utilizing Structural Redundancy in Vessel Networks"
date: 2020-01-01
publishDate: 2020-04-17T13:51:41.933452Z
authors: ["Liangzhi Li", "Manisha Verma", "Yuta Nakashima", "Hajime Nagahara", "Ryo Kawasaki"]
publication_types: ["1"]
publication: "*The IEEE Winter Conference on Applications of Computer Vision*"


abstract: "Retinal vessel segmentation is of great interest for diagnosis of retinal vascular diseases. To further improve the performance of vessel segmentation, we propose IterNet, a new model based on UNet, with the ability to find obscured details of the vessel from the segmented vessel image itself, rather than the raw input image. IterNet consists of multiple iterations of a mini-UNet, which can be 4× deeper than the common UNet. IterNet also adopts the weight-sharing and skip-connection features to facilitate training; therefore, even with such a large architecture, IterNet can still learn from merely 10∼20 labeled images, without pre-training or any prior knowledge. IterNet achieves AUCs of 0.9816, 0.9851, and 0.9881 on three mainstream datasets, namely DRIVE, CHASE-DB1, and STARE, respectively, which currently are the best scores in the literature. The source code is available."
featured: true
doi: ""
url_pdf: "paper/li-2020-iternet.pdf"
url_code: "https://github.com/conscienceli/IterNet"
url_dataset: ""
url_poster: "poster/wacv20.pdf"
url_project: ""
url_slides: ""
url_source: ""
url_video: "https://youtu.be/i-4pGCJrKa4?t=3283"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

