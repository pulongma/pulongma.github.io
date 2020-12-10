---
layout: post
title:  "RESEARCH"
categories: jekyll update
---

Uncertainty Quantification for Coastal Flood Hazard Studies
======

Hurricane-driven storm surge is one of the most deadly and costly natural disasters, making precise quantification of the surge hazard of great importance. current coastal flood hazard studies are often performed through a synthesis of computer modeling, statistical modeling, and extreme-event probability computation, where computer modeling is used to predict the storm surge hazard initialized by hurricanes, statistical modeling is used to determine the distribution of hurricane characteristics, and extreme-event probability is used to assess the flood hazard. These studies support development and application of flood insurance rates, building codes, land use planning/development, infrastructure design and construction, and related goals by providing hazard levels at a range of frequencies. However, current coastal flood hazard studies have suffered from several limitations including exceesive usage of computing resources, inappropriate uncertainty quantification, and lack of optimal statistical modeling. Current UQ for coastal flood hazard studies is prohibitively costly and unrealistic. Part of my research has focused on developing efficient and rigorous UQ methodologies to facilitate coastal flood hazard studies.  



------
Uncertainty Quantification in Assessing Storm Surges 
===
Storm surge is one of the most severe natural hazards that can lead to significant flooding in coastal areas and severe damages to the life and property from a hurricane. To assess storm surge hazards, current coastal flood hazard studies are often performed through a synthesis of computer modeling, statistical modeling, and extreme-event probability computation.  Since post-Katrina coastal flood hazard studies, a key technique called Joint Probability Method (JPM) and its improvements has become the gold standard to compute annual exceedance probabilities (AEP) levels at certain frequencies by federal agencies such as Federal Emergency Management Agency (FEMA) and US Amy Corps of Engineers (USACE), private sectors, and academic researches in coastal engineering. However, the JPM  suffers several disadvantages including exceesive usage of computing resources, inappropriate uncertainty quantification, and lack of optimal statistical modeling, which make the JPM based coastal flood hazard studies prohibitively costly and unrealistic. To address these issues, we employ a new risk assessment framework to assess storm surges hazards in Southwest Florida (SWFL), by developing an emulator called zero-inflated Gaussian process (ZiGP) - a fast approximation to the computer model of storm surges, and by efficient sampling from the joint distribution of storm characteristics to enable efficient computation of AEP. 


------
Multifidelity Computer Model Emulation for Storm Surges
===
Hurricane-driven storm surge is one of the most deadly and costly natural disasters, making precise quantification of the surge hazard of great importance. Inference of such systems is done through physics-based computer models of the process. Such surge simulators can be implemented with a wide range of fidelity levels, with computational burdens varying by several orders of magnitude due to the nature of the system. The danger posed by surge makes greater fidelity highly desirable, however such models and their high-volume output tend to come at great computational cost, which can make detailed study of coastal flood hazards prohibitive. These needs make the development of an emulator combining high-dimensional output from multiple complex computer models with different fidelity levels important. We propose a parallel partial autoregressive cokriging model to predict highly-accurate storm surges in a computationally efficient way over a large spatial domain. This emulator has the capability of predicting storm surges as accurately as a high-fidelity computer model given any storm characteristics and allows accurate assessment of the hazards from storm surges over a large spatial domain.

![SWAN+ADCIRC simulation](/images/map_tesing_run_161_selected_LHS4A.png)
![PP cokriging predictions](/images/map_predmu_run_161_selected_LHS4A.png)
![PP cokriging standard Errors](/images/map_predSE_run_161_selected_LHS4A.png)



------
Relevant References 
------
<!-- Ma, P., Berger, J. O., Asher, T. G., Toro, G. R., and Cox, A. T. "Uncertainty Quantification in Assessing Storm Surges". In preparation. -->


Ma, P., Karagiannis, G., Konomi, B. A., Asher, T. G., Toro, G. R., and Cox, A. T. (2020) "Multifidelity Computer Model Emulation with High-Dimensional Output: An Application to Storm Surge." <em>Journal of the Royal Statistical Society: Series C</em>. In Revision. <a href="https://arxiv.org/abs/1909.01836" target="blank" style="color:blue;">arXiv:1909.01836.</a>

Ma, P. (2020). "Objective Bayesian Analysis of a Cokriging Model for Hierarchical Multifidelity Codes" <em>SIAM/ASA Journal on Uncertainty Quantification</em>, 8(4), 1358-1382. <a href="https://doi.org/10.1137/19M1289893" style="color:blue;">DOI:10.1137/19M1289893
