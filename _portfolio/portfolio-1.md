---
title: "Mapping of Soil Erosion in the Upper Molopo River Catchment Using GIS and Remote Sensing"
collection: portfolio
permalink: /portfolio/soil-erosion-gis-rusle
date: 2021-12-01
excerpt: "Honours research project applying RUSLE in a GIS and remote sensing framework to assess erosion risk in the Upper Molopo River Catchment."
---

### 🗺️ Mapping of Soil Erosion in the Upper Molopo River Catchment Using GIS and Remote Sensing  
**BSc Honours Research Project**  
**University of Pretoria**

This project focused on estimating and mapping soil erosion risk in the Upper Molopo River Catchment (UMRC) using the Revised Universal Soil Loss Equation (RUSLE) model integrated within a GIS and Remote Sensing framework. Due to limited field data, all RUSLE parameters (R, K, LS, C, and P) were derived using remote sensing, spatial interpolation, and publicly available datasets.

---

#### 🔍 Methods and Tools Used

- **Rainfall Erosivity (R)**: Calculated using rainfall records from 2014–2018 based on the Wischmeier and Smith (1978) equation.
- **Soil Erodibility (K)**: Estimated from ISRIC Soil Info data at 24 GPS-logged sites. Interpolated using Inverse Distance Weighting (IDW) in ArcGIS.
- **Topographic Factor (LS)**: Derived from DEM using slope and flow accumulation in ArcGIS and ERDAS Imagine.
- **Cover Management (C)**: Computed using NDVI from Spot vegetation imagery and classified using ArcGIS spatial analyst tools.
- **Support Practice (P)**: Assigned a value of 1 due to absence of conservation practices in the area.
- **Annual Soil Loss**: Final raster calculated using ArcGIS Raster Calculator applying the full RUSLE equation: `A = R * K * LS * C * P`.

---

#### 🧰 Skills Applied

- Spatial analysis  
- GIS modelling (ArcGIS 10.6, ERDAS Imagine)  
- Satellite image processing (NDVI analysis)  
- Soil data acquisition (ISRIC Soil App, GPS mapping)  
- Environmental modelling using RUSLE  
- Spatial interpolation techniques (IDW)  
- Remote sensing and geospatial data visualization  
- Python scripting (where applicable)

---

#### 🌱 Impact

This project produced a spatially explicit map of soil erosion risk, identifying high-risk zones within the catchment. The outputs provide a foundation for future land use planning and conservation, especially in data-scarce regions. The study also demonstrates the potential of remote sensing and open-access data to conduct robust environmental assessments in under-resourced areas.
