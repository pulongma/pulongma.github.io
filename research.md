---
layout: default
title: RESEARCH
mathjax: true
---


Research Interests
= 
<p style="text-align: justify; line-height: 1.2em;">  
My statistical research is stimulated by real-world challenges and aims at addressing real-world problems in physical sciences including remote sensing science and climate science, engineering, and medical science. My research interest is focused on developing statistical methods for understanding physical and environmental processes. It spans the following areas of statistics and machine learning:
<ul>
  <li> <b>Uncertainty Quantification (UQ)</b>: Computer model validation, computer model emulation, model discrepancy, Bayesian calibration</li>
  
  <li><b>Bayesian Statistics</b>: Nonparametric Bayes, objective Bayes, Bayesian hierarchical modeling and computation, Bayesian variable selection, model uncertainty </li>
  
  <li> <b>Spatial and Spatio-Temporal Statistics</b>: Random fields, nonstationary space-time processes, dynamic spatio-temporal models, multivariate models, data fusion </li>
</ul>
</p>

<p style="text-align: justify; line-height: 1.2em;">
I work with climate scientists and ocean scientists to address data analytic problems in remote sensing and coastal flood hazard studies. Motivated by such interdisciplinary collaboration, I recently focus on developing statistical methods that allow flexible model structures and scalable computations for analyzing big and complex data with spatial dependence and understanding their use in complex real-world applications including environmental mapping, probabilistic assessment of remote sensing retrievals, and risk assessment of storm surges. More specifically, they can be summarized into three directions:
<ul>
    <li> Bayesian multi-scale methods and tree-based methods for Gaussian process modeling and their theoretical properties; (research supported by <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2152998&HistoricalAwards=false" target="blank" style="color:blue;">NSF DMS-2152998</a>) </li> 
  <li> Bayesian-frequentist theoretical foundations on constructing covariance function models and their practical usefulness; </li>
  <li> Bayesian methods for emulating, calibrating, and validating complex computer models with high-dimensional/functional input and massive functional/spatial outputs. </li> 
  </ul>
</p>
<br/>

<!--
Research Support
= 
<div style="text-align: justify; line-height: 1.2em;">
  
My research is currently supported by NSF CDS&E-MSS Program DMS-2152998. Prior support: SAMSI Postdoctoral Fellowship and USCRP grant.  

</div>
<br/>
-->

Research Projects
=

### Uncertainty Quantification for Remote Sensing 
<div style="text-align: justify; line-height: 1.2em;">
With space-based observations, remote sensing technology provides a wealth of information for understanding geophysical processes with unprecedented spatial and temporal coverage. Quantitative inference for the global carbon cycle has been bolstered by greenhouse gas observing satellites. <a href="https://ocov2.jpl.nasa.gov/" target="blank" style="color:blue;">NASA’s Orbiting Carbon Observatory-2 (OCO-2)</a> collects tens of thousands of observations of reflected sunlight daily. These observed spectra, or radiances, are used to infer the atmospheric carbon dioxide (CO2) at fine spatial and temporal resolution with substantial coverage across the globe. Estimates of atmospheric CO2 are computed from the observed radiances using an inverse method known as a retrieval algorithm. The resulting estimates of geophysical quantities of interest are called retrievals. A key task in remote sensing science is to perform probabilistic assessment of remote sensing retrievals. However, different from many other disciplines, it is infeasible to perform physical experiments to study the quality of remote sensing retrievals thoroughly because a representative ground truth of atmospheric variables is usually lacking. Collobrating with scientists at NASA JPL, my research is focused on developing UQ methodologies to facilitate probabilistic assessment of remote sensing retrievals. <!--<a href="/_research/UQRemoteSensing.md" target="blank">See more</a>. -->
<br>
<br>

<li> <b>Spatial Mapping for OCO-2 Data</b> <br>
  <ul> <b> Ma, P.</b> and Bhadra, A. (2022) "<a href="https://arxiv.org/abs/1911.05865" target="blank" style="color:blue;">Beyond Mat&eacute;rn: On A Class of Interpretable Confluent Hypergeometric Covariance Functions</a>." <em>Journal of the American Statistical Association, Theory and Methods</em>. DOI:10.1080/01621459.2022.2027775. </ul>
 </li>

<li> <b>Surrogate Modeling in Observing System Uncertainty Experiments in the OCO-2/3 Missions</b> <br>
  <ul> <b> Ma, P.</b>, Mondal, A., Konomi, B. A., Hobbs, J., Song, J. J., and Kang, E. L. (2021) "<a href="https://doi.org/10.1080/00401706.2021.1895890" target="blank" style="color:blue;">Computer Model Emulation with High-Dimensional Functional Output in Large-Scale Observing System Uncertainty Experiments</a>." <em>Technometrics</em>. DOI:10.1080/00401706.2021.1895890. </ul>
</li> 

<li> <b>Spatial Downscaling in Observing System Simulation Experiments</b> <br> 
  <ul><b>Ma, P.</b>, Kang, E. L., Braverman, A., and Nguyen, H. (2019) "<a href="https://doi.org/10.1080/00401706.2018.1524791" target="blank" style="color:blue;">Spatial Statistical Downscaling for Constructing High-Resolution Nature Runs in Global Observing System Simulation Experiments</a>." <em>Technometrics</em>, 61(3), 322-340. </ul>
</li>

</div>
<br>


### Uncertainty Quantification for Coastal Flood Hazard Studies
<div style="text-align: justify; line-height: 1.2em;">
Hurricane-driven <a href="https://www.nhc.noaa.gov/surge/" target="blank" style="color:blue;">storm surge</a> is one of the most deadly and costly natural disasters, making precise quantification of the surge hazard of great importance. Current coastal flood hazard studies are often performed through a synthesis of computer modeling, statistical modeling, and extreme-event probability computation, where computer modeling is used to predict the storm surge hazard initialized by hurricanes, statistical modeling is used to determine the distribution of hurricane characteristics, and extreme-event probability is used to assess the flood hazard. These studies support development and application of flood insurance rates, building codes, land use planning/development, infrastructure design and construction, and related goals by providing hazard levels at a range of frequencies. However, current coastal flood hazard studies have suffered from several limitations including tremendous amount of computing resources, inappropriate uncertainty quantification, and lack of optimal statistical modeling. Collaborating with ocean scientists at University of North Carolina, Chapel Hill, my research is focused on developing computationally efficient and rigorous UQ methodologies to facilitate coastal flood hazard studies. <!-- <a href="/_research/UQCoastalFlood.md" target="blank">See more</a>.-->
<br>
<br>

<li> <b>Multifidelity Computer Model Emulation for Storm Surges</b> <br>
 <ul> <b> Ma, P.</b>, Karagiannis, G., Konomi, B. A., Asher, T. G., Toro, G. R., and Cox, A. T. (2022) "<a href="https://arxiv.org/abs/1909.01836" target="blank" style="color:blue;">Multifidelity Computer Model Emulation with High-Dimensional Output: An Application to Storm Surge</a>." <em>Journal of the Royal Statistical Society: Series C</em>. DOI:https://doi.org/10.1111/rssc.12558. </ul>
</li>
 
<li> <b>Objective Bayes for Multifidelity Computer Models</b> <br>
  <ul> <b> Ma, P.</b> (2020) "<a href="https://epubs.siam.org/doi/10.1137/19M1289893" target="blank" style="color:blue;">Objective Bayesian Analysis of a Cokriging Model for Hierarchical Multifidelity Codes</a>." <em>SIAM/ASA Journal on Uncertainty Quantification</em>, 8(4), 1358-1382. </ul>
</li>


</div>

