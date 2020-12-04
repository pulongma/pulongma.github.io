---
layout: post
title:  "Research Highlights"
categories: jekyll update
---

Uncertainty Quantification for Remote Sensing Science
======

Surroage Modeling in OCO-2/3 Missions
===
Observing system uncertainty experiments (OSUEs) have been recently proposed as a cost-effective way to perform probabilistic assessment of retrievals for NASA's Orbiting Carbon Observatory-2 (OCO-2) mission. One important component in the OCO-2 retrieval algorithm is a full-physics (FP) forward model that describes the mathematical relationship between atmospheric variables such as carbon dioxide and radiances measured by the remote sensing instrument. This forward model is nonlinear and computationally expensive but large-scale OSUEs require evaluation of this model numerous times, which makes it infeasible for comprehensive experiments. To tackle this issue, this paper develops a statistical emulator to facilitate large-scale OSUEs in the OCO-2 mission with independent emulation. Within each distinct spectral band, the emulator represents radiances output at irregular wavelengths via a linear combination of basis functions and random coefficients. These random coefficients are then modeled with nearest-neighbor Gaussian processes (NNGP) with built-in input dimension reduction via active subspace. The proposed emulator reduces dimensionality in both input space and output space, so that fast computation is achieved within a fully Bayesian inference framework. Validation experiments demonstrate that this emulator outperforms other competing statistical methods and a reduced order model (ROM) that approximates the full-physics forward model. 

![OCO-2 full-physics forward model simulation over five soundings](/images/soundings_examples_OCO2.jpg)
![Comparison of the FP forward model simulated radiances, the ROM predictions, and the predicted radiances with their 95\% credible intervals from the band-independent emulator (IND) based on NNGP](/images/IND_ROM_15.jpg)

<!-- {% include image.html url="/images/soundings_examples_OCO2.jpg" description="OCO-2 full-physics forward model simulation over five soundings" %} !>


------
References 
------
<b> Ma, P.</b>, Mondal, A., Konomi, B. A., Hobbs, J., Song, J. J., and Kang, E. L. (2020) "Computer Model Emulation with High-Dimensional Functional Output in Large-Scale Observing System Uncertainty Experiments." <em>Technometrics</em>. In Revision. <a href="https://arxiv.org/abs/1911.09274" target="blank" style="color:blue;">arXiv:1911.09274.</a>

[Ma2020OSUE]: https://arxiv.org/abs/1911.09274 
