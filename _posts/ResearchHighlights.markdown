---
layout: post
title:  "Research Highlights"
categories: jekyll update
---

Observing system uncertainty experiments (OSUEs) have been recently proposed as a cost-effective way to perform probabilistic assessment of retrievals for NASA's Orbiting Carbon Observatory-2 (OCO-2) mission. One important component in the OCO-2 retrieval algorithm is a full-physics forward model that describes the mathematical relationship between atmospheric variables such as carbon dioxide and radiances measured by the remote sensing instrument. This forward model is complicated and computationally expensive but large-scale OSUEs require evaluation of this model numerous times, which makes it infeasible for comprehensive experiments. To tackle this issue, this paper develops a statistical emulator to facilitate large-scale OSUEs in the OCO-2 mission with independent emulation. Within each distinct spectral band, the emulator represents radiances output at irregular wavelengths via a linear combination of basis functions and random coefficients. These random coefficients are then modeled with nearest-neighbor Gaussian processes with built-in input dimension reduction via active subspace. The proposed emulator reduces dimensionality in both input space and output space, so that fast computation is achieved within a fully Bayesian inference framework. Validation experiments demonstrate that this emulator outperforms other competing statistical methods and a reduced order model that approximates the full-physics forward model. For more details, see [Ma2020OSUE][the preprint].  

[Ma2020OSUE]: https://arxiv.org/abs/1911.09274 
