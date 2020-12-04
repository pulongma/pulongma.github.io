---
layout: post
title:  "Research Highlights"
categories: jekyll update
---

Uncertainty Quantification for Coastal Flood Hazard Studies

======

Multifidelity Computer Modeling for Storm Surges
===
Hurricane-driven storm surge is one of the most deadly and costly natural disasters, making precise quantification of the surge hazard of great importance. Inference of such systems is done through physics-based computer models of the process. Such surge simulators can be implemented with a wide range of fidelity levels, with computational burdens varying by several orders of magnitude due to the nature of the system. The danger posed by surge makes greater fidelity highly desirable, however such models and their high-volume output tend to come at great computational cost, which can make detailed study of coastal flood hazards prohibitive. These needs make the development of an emulator combining high-dimensional output from multiple complex computer models with different fidelity levels important. We propose a parallel partial autoregressive cokriging model to predict highly-accurate storm surges in a computationally efficient way over a large spatial domain. This emulator has the capability of predicting storm surges as accurately as a high-fidelity computer model given any storm characteristics and allows accurate assessment of the hazards from storm surges over a large spatial domain.

![SWAN+ADCIRC simulation](/images/map_tesing_run_161_selected_LHS4A.png)
![PP cokriging predictions](/images/map_predmu_run_161_selected_LHS4A.png)
![PP cokriging standard Errors](/images/map_predSE_run_161_selected_LHS4A.png)



------
References 
------
Ma, P., Karagiannis, G., Konomi, B. A., Asher, T. G., Toro, G. R., and Cox, A. T. (2020) "Multifidelity Computer Model Emulation with High-Dimensional Output: An Application to Storm Surge." <em>Journal of the Royal Statistical Society: Series C</em>. In Revision. <a href="https://arxiv.org/abs/1909.01836" target="blank" style="color:blue;">arXiv:1909.01836.</a>
