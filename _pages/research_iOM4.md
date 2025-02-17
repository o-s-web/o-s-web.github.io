---
permalink: /research_iOM4/
title:  "Global Ocean-Cryosphere Model iOM"
layout: splash
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: "movie_iOM4_v1.gif"

---

iOM is a global ocean-cryosphere model with all components of the polar cryosphere -- ice sheets, sea ice and icebergs -- coupled to the ocean. 

<p align="center">
  <img src="/images/iOM_symbols.png" alt="iOM schematic" style="width: 600px;"/>
</p>

[**MOM6**](https://github.com/NOAA-GFDL/MOM6-examples/wiki), is the ocean component. Among its many unique features, **MOM6** has an ability to represent the vertical ocean structure in any kind of vertical coordinates, such as geopotential, isopycnal, terrain-following, or any other [(*Adcroft et al.*,2019)](https://doi.org/10.1029/2019MS001726). Such capabilities allow it to accurately represent circulation in sub-ice-shelf cavities and their evolution, including due to the migration of the grounding lines.

[**MOM6-IS**](https://github.com/NOAA-GFDL/MOM6/tree/dev/gfdl/src/ice_shelf) is the ice-sheet component. **MOM6-IS** is built as a component of **MOM6**. Both models use the same horizontal grid. This allows to accurately simulate ice-sheet ocean interactions and evolution of marine ice sheets.  **MOM6-IS** can run coupled to MOM6 as well as stand alone.

[**SIS2**](https://github.com/NOAA-GFDL/MOM6-examples/wiki) is the sea-ice component. **SIS2** simulates sea ice as an elastic-viscous-plastic material. It simulates evolution of sea-ice thickness, temperature, salinity and enthalpy due to energy, mass and salt exchanges with the ocean and atmosphere [*Adcroft et al.* (2019)](https://doi.org/10.1029/2019MS001726). 

[**KID**](https://github.com/NOAA-GFDL/icebergs) is the iceberg component. **KID** simulates icebergs as Lagrangian particles that move, melt and erode [(*Stearn et al.*, 2016)](https://doi.org/10.1002/2016JC011835). The large icebergs are represented as a collection of Lagrangian particles connected by numerical bonds [(*Stern et al.*, 2017)](https://doi.org/10.1002/2017MS001002).


All model components are available under an open-development software framework. Its details can be found on [MOM6 wiki](https://github.com/NOAA-GFDL/MOM6-examples/wiki).  
