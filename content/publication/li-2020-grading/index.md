---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Grading the Severity of Arteriolosclerosis from Retinal Arterio-venous Crossing
  Patterns
subtitle: ''
summary: ''
authors:
- Liangzhi Li
- Manisha Verma
- Bowen Wang
- Yuta Nakashima
- Ryo Kawasaki
- Hajime Nagahara
tags: []
categories: []
date: '2020-11-10'
lastmod: 2020-11-15T13:02:41+09:00
featured: false
draft: false

doi: ""
url_pdf: "paper/li-2020-grading.pdf"
url_code: "https://github.com/conscienceli/MDTNet"
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
# publication_types: use the following legend to specify the type of your publication, e.g. "1" for conference proceedings:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis (v4.2+ required)
# 8 = Patent (v4.2+ required)
projects: []
publishDate: '2020-11-10T03:52:53.928825Z'
publication_types:
- 0
abstract: "The status of retinal arteriovenous crossing is of great significance for clinical evaluation of arteriolosclerosis and systemic hypertension. As an ophthalmology diagnostic criteria, Scheie's classification has been used to grade the severity of arteriolosclerosis. In this paper, we propose a deep learning approach to support the diagnosis process, which, to the best of our knowledge, is one of the earliest attempts in medical imaging. The proposed pipeline is three-fold. First, we adopt segmentation and classification models to automatically obtain vessels in a retinal image with the corresponding artery/vein labels and find candidate arteriovenous crossing points. Second, we use a classification model to validate the true crossing point. At last, the grade of severity for the vessel crossings is classified. To better address the problem of label ambiguity and imbalanced label distribution, we propose a new model, named multi-diagnosis team network (MDTNet), in which the sub-models with different structures or different loss functions provide different decisions. MDTNet unifies these diverse theories to give the final decision with high accuracy. Our severity grading method was able to validate crossing points with precision and recall of 96.3% and 96.3%, respectively. Among correctly detected crossing points, the kappa value for the agreement between the grading by a retina specialist and the estimated score was 0.85, with an accuracy of 0.92. The numerical results demonstrate that our method can achieve a good performance in both arteriovenous crossing validation and severity grading tasks. By the proposed models, we could build a pipeline reproducing retina specialist's subjective grading without feature extractions. The code is available for reproducibility."
publication: 'arXiv preprint'
---
