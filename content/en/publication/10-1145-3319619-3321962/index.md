---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Balancing Exploration and Exploitation in Multiobjective Batch Bayesian Optimization
subtitle: ''
summary: ''
authors:
- Hongyan Wang
- Hua Xu
- Yuan Yuan
- Xiaomin Sun
- Junhui Deng
tags:
- '"batch bayesian optimization"'
- '"expensive multiobjective optimization"'
- '"exploration and exploitation"'
- '"gaussian process"'
- '"ParEGO"'
categories: []
date: '2019-01-01'
lastmod: 2020-09-19T21:55:28+08:00
featured: false
draft: false

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
publishDate: '2020-09-19T13:55:27.195975Z'
publication_types:
- 1
abstract: Many applications such as hyper-parameter tunning in Machine Learning can
  be casted to multiobjective black-box problems and it is challenging to optimize
  them. Bayesian Optimization (BO) is an effective method to deal with black-box functions.
  This paper mainly focuses on balancing exploration and exploitation in multi-objective
  black-box optimization problems by multiple samplings in BBO. In each iteration,
  multiple recommendations are generated via two different trade-off strategies respectively
  the expected improvement (EI) and a multiobjective framework with the mean and variance
  function of the GP posterior forming two conflict objectives. We compare our algorithm
  with ParEGO by running on 12 test functions. Hypervolume (HV, also known as S-metric)
  results show that our algorithm works well in exploration-exploitation trade-off
  for multiobjective black-box optimization problems.
publication: '*Proceedings of the Genetic and Evolutionary Computation Conference
  Companion*'
url_pdf: https://doi.org/10.1145/3319619.3321962
doi: 10.1145/3319619.3321962
---