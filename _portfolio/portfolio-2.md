---
title: "Learning Ocean Vertical Mixing from Large-Eddy Simulations"
excerpt: "Developing physics-informed deep learning parameterizations for ocean vertical mixing using high-resolution LES datasets, with online evaluation in LICOM3.0<br/><img src='/images/Fig8_in_VMP.png' width='600' height='450' style='background-color:white; display:block; margin:0 auto;'>"
collection: portfolio
---

### Motivation
Vertical mixing parameterization is a major source of uncertainty in ocean circulation models. Traditional schemes are empirically developed without thorough understanding of the physical processes involved. Deep learning offers a promising pathway to capture complex nonlinear mixing processes directly from high-fidelity data.

### Approach
- Constructed high-resolution turbulence-resolving datasets using large-eddy simulations (LES) driven by diurnal external forcings (wind-stress and net heat flux)
- Designed training strategies linking resolved turbulence statistics to subgrid-scale parameterization targets
- Implemented the learned parameterization into LICOM3.0 for online coupled simulations
- Evaluated impacts on large-scale ocean circulation and climate variability

### Previous Work: DLVMP in LICOM3.0
Prior to the LES-based approach, implemented the deep-learning-based vertical mixing parameterization (DLVMP, Fang et al., 2025) into LICOM3.0:
- DLVMP inherits KPP biases but improves equatorial subsurface temperature climatology due to inclusion of observational information
- Compared to Canuto2001, both DLVMP and KPP underestimate surface mixing and overestimate subsurface mixing in the equatorial Pacific
- Biases lead to significant differences in temperature, salinity, mixed-layer depth, AMOC, and STC
- Underestimated surface mixing weakens mid-latitude ventilation, causing STC intensification and thermocline cold bias

### Publications
- Yongqiang Yu, **Jin Li**, Xiaojie Li. (2025). Application and Evaluation of an Artificial Intelligence Vertical Mixing Parameterization in an Ocean Model. *Chinese Journal of Atmospheric Sciences*.
- Junjie Fang, Xiaojie Li, **Jin Li**, Zhanao Huang, Yongqiang Yu, Xiaomeng Huang, Xi Wu. (2025). Physically Constrained Adaptive Deep Learning for Ocean Vertical-Mixing Parameterization. *Advances in Atmospheric Sciences*, 42(1), 165–177.
