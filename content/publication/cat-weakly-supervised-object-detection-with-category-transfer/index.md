---
title: "CaT: Weakly Supervised Object Detection With Category Transfer"
publication_types:
  - "1"
authors:
  - Tianyue Cao
  - Lianyu Du
  - Xiaoyun Zhang
  - Siheng Chen
  - Ya Zhang
  - Yan-Feng Wang
publication_short: In *ICCV 2021*
abstract: A large gap exists between fully-supervised object detection and
  weakly-supervised object detection. To narrow this gap, some methods consider
  knowledge transfer from additional fully-supervised dataset. But these methods
  do not fully exploit discriminative category information in the
  fully-supervised dataset, thus causing low mAP. To solve this issue, we
  propose a novel category transfer framework for weakly supervised object
  detection. The intuition is to fully leverage both visually-discriminative and
  semantically-correlated category information in the fully-supervised dataset
  to enhance the object-classification ability of a weakly-supervised detector.
  To handle overlapping category transfer, we propose a double-supervision mean
  teacher to gather common category information and bridge the domain gap
  between two datasets. To handle non-overlapping category transfer, we propose
  a semantic graph convolutional network to promote the aggregation of semantic
  features between correlated categories. Experiments are conducted with Pascal
  VOC 2007 as the target weakly-supervised dataset and COCO as the source
  fully-supervised dataset. Our category transfer framework achieves 63.5% mAP
  and 80.3% CorLoc with 5 overlapping categories between two datasets, which
  outperforms the state-of-the-art methods. Codes are avaliable at
  https://github.com/MediaBrain-SJTU/CaT.
draft: false
featured: true
tags: []
slides: ""
url_pdf: "https://openaccess.thecvf.com/content/ICCV2021/papers/Cao_CaT_Weakly_Supervised_Object_Detection_With_Category_Transfer_ICCV_2021_paper.pdf"
image:
  caption: the architecture of CaT
  focal_point: ""
  preview_only: false
  filename: featured.png
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: ""
publication: In *International Conference on Computer Vision*
projects: []
date: 2021-10-12T02:29:08.288Z
url_slides: ""
publishDate: 2021-10-12T00:00:00.000Z
url_poster: ""
url_code: "https://github.com/MediaBrain-SJTU/CaT"
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
