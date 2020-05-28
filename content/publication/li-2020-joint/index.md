---
title: "Joint Learning of Vessel Segmentation and Artery/Vein Classification with Post-processing"
date: 2020-01-01
publishDate: 2020-05-28T00:37:42.999282Z
authors: ["Liangzhi Li", "Manisha Verma", "Yuta Nakashima", "Ryo Kawasaki", "Hajime Nagahara"]
publication_types: ["1"]

abstract: "Retinal imaging serves as a valuable tool for diagnosis of various diseases. However, reading retinal images is a difficult and time-consuming task even for experienced specialists. The fundamental step towards automated retinal image analysis is vessel segmentation and artery/vein classification, which provide various information on potential disorders. To improve the performance of the existing automated methods for retinal image analysis, we propose a two-step vessel classification. We adopt a UNet-based model, SeqNet, to accurately segment vessels from the background and make prediction on the vessel type. Our model does segmentation and classification sequentially, which alleviates the problem of label distribution bias and facilitates training. To further refine classification results, we post-process them considering the structural information among vessels to propagate highly confident prediction to surrounding vessels. Our experiments show that our method improves AUC to 0.98 for segmentation and the accuracy to 0.92 in classification over DRIVE dataset."
featured: false
publication: "Medical Imaging with Deep Learning (MIDL) 2020"
doi: ""
url_pdf: "https://arxiv.org/pdf/2005.13337.pdf"
url_code: ""
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
---

