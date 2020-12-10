---
layout: post
title:  "UQ for Remote Sensing"
---

Uncertainty Quantification for Remote Sensing Science
======
With space-based observations, remote sensing technology provides a wealth of information for understanding geophysical processes with unprecedented spatial and temporal coverage. Quantitative inference for the global carbon cycle has been bolstered by greenhouse gas observing satellites. NASA’s Orbiting Carbon Observatory-2 (OCO-2) collects tens of thou- sands of observations of reflected sunlight daily. These observed spectra, or radiances, are used to infer the atmospheric carbon dioxide (CO2) at fine spatial and temporal resolution with substantial coverage across the globe. Estimates of atmospheric CO2 are computed from the observed radiances using an inverse method known as a retrieval algorithm. The resulting estimates of geophysical quantities of interest are called retrievals. A key task in remote sensing science is to perform probabilistic assessment of remote sensing retrievals. However, different from many other disciplines, it is infeasible to perform physical experiments to study the quality of remote sensing retrievals thoroughly because a representative ground truth of atmospheric variables is usually lacking. Part of my research has focused on developing UQ methodologies to facilitate probabilistic assessment of remote sensing retrievals. 

------
Surroage Modeling in OCO-2/3 Missions
===
Observing system uncertainty experiments (OSUEs) have been recently proposed as a cost-effective way to perform probabilistic assessment of retrievals for NASA's Orbiting Carbon Observatory-2 (OCO-2) mission. One important component in the OCO-2 retrieval algorithm is a full-physics (FP) forward model that describes the mathematical relationship between atmospheric variables such as carbon dioxide and radiances measured by the remote sensing instrument. This forward model is nonlinear and computationally expensive but large-scale OSUEs require evaluation of this model numerous times, which makes it infeasible for comprehensive experiments. To tackle this issue, this paper develops a statistical emulator to facilitate large-scale OSUEs in the OCO-2 mission with independent emulation. Within each distinct spectral band, the emulator represents radiances output at irregular wavelengths via a linear combination of basis functions and random coefficients. These random coefficients are then modeled with nearest-neighbor Gaussian processes (NNGP) with built-in input dimension reduction via active subspace. The proposed emulator reduces dimensionality in both input space and output space, so that fast computation is achieved within a fully Bayesian inference framework. Validation experiments demonstrate that this emulator outperforms other competing statistical methods and a reduced order model (ROM) that approximates the full-physics forward model. 

![OCO-2 full-physics forward model simulation over five soundings](/images/soundings_examples_OCO2.jpg)
![Comparison of the FP forward model simulated radiances, the ROM predictions, and the predicted radiances with their 95\% credible intervals from the band-independent emulator (IND) based on NNGP](/images/IND_ROM_15.jpg)



------
Relevant References 
------
<b> Ma, P.</b>, Mondal, A., Konomi, B. A., Hobbs, J., Song, J. J., and Kang, E. L. (2020) "Computer Model Emulation with High-Dimensional Functional Output in Large-Scale Observing System Uncertainty Experiments." <em>Technometrics</em>. In Revision. <a href="https://arxiv.org/abs/1911.09274" target="blank" style="color:blue;">arXiv:1911.09274.</a>

