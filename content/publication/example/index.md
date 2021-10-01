---
title: Logarithmic landscape and power-law escape rate of SGD
publication_types:
  - "3"
authors:
  - Takashi Mori
  - Liu Ziyin
  - Kangqiao Liu
  - and Masahito Ueda
publication_short: ""
abstract: Stochastic gradient descent (SGD) undergoes complicated multiplicative
  noise for the mean-square loss. We use this property of the SGD noise to
  derive a stochastic differential equation (SDE) with simpler additive noise by
  performing a non-uniform transformation of the time variable. In the SDE, the
  gradient of the loss is replaced by that of the logarithmized loss.
  Consequently, we show that, near a local or global minimum, the stationary
  distribution P_ss(θ) of the network parameters θ follows a power-law with
  respect to the loss function L(θ), i.e. P_ss(θ)∝L(θ)−ϕ with the exponent ϕ
  specified by the mini-batch size, the learning rate, and the Hessian at the
  minimum. We obtain the escape rate formula from a local minimum, which is
  determined not by the loss barrier height ΔL=L(θ_s)−L(θ^∗) between a minimum
  θ^∗ and a saddle θs but by the logarithmized loss barrier height
  ΔlogL=log[L(θ_s)/L(θ^∗)]. Our escape-rate formula explains an empirical fact
  that SGD prefers flat minima with low effective dimensions.
draft: false
featured: false
tags: []
slides: ""
url_pdf: ""
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: https://arxiv.org/abs/2105.09557
publication: ""
projects: []
date: 2021-10-01T07:40:58.278Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
