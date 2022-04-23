---
title: Learning to Learn Graph Topologies
publication_types:
  - "1"
authors:
  - Xingyue Pu
  - Tianyue Cao
  - Xiaoyun Zhang
  - Xiaowen Dong
  - Siheng Chen
publication_short: In *NeruIPS 2021*
abstract: Learning a graph topology to reveal the underlying relationship
  between data entities plays an important role in various machine learning and
  data analysis tasks. Under the assumption that structured data vary smoothly
  over a graph, the problem can be formulated as a regularised convex
  optimisation over a positive semidefinite cone and solved by iterative
  algorithms. Classic methods require an explicit convex function to reflect
  generic topological priors, e.g. the ℓ1 penalty for enforcing sparsity, which
  limits the flexibility and expressiveness in learning rich topological
  structures. We propose to learn a mapping from node data to the graph
  structure based on the idea of learning to optimise (L2O). Specifically, our
  model first unrolls an iterative primal-dual splitting algorithm into a neural
  network. The key structural proximal projection is replaced with a variational
  autoencoder that refines the estimated graph with enhanced topological
  properties. The model is trained in an end-to-end fashion with pairs of node
  data and graph samples. Experiments on both synthetic and real-world data
  demonstrate that our model is more efficient than classic iterative algorithms
  in learning a graph with specific topological properties.
draft: false
featured: true
tags: []
slides: example
url_pdf: ""
image:
  caption: an illustration of the proposed framework
  focal_point: ""
  preview_only: false
  filename: ""
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: ""
publication: In *Conference on Neural Information Processing Systems*
projects: []
date: 2021-12-06T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
