# Remote Sensing Project
[Remote sensing data workflow and visualization using Environment Canada satellite data.] 

## About the Project

## Python Data Cleaning Workflow
### Corbel Spatial Geospatial Wheels Index
**GitHub**: [Corbel Spatial Wheels](https://github.com/corbel-spatial/geospatial-wheels-index)
### Earth Engine
### Data Preparation

## Python Data Analysis Workflow
### Statistical Analysis
### K-means and RandomForest 

## Blender Simulation
![Elevation Render](./Assets/geometry_nodes.png)
![Project Banner](./Assets/Edited_Renders/3_raster_set_orthographic_2.jpg)

## Future Work
Additional exploratory work investigated LiDAR and Landsat in the ROI; these are not included in the main analysis. Future expansions may include the following:
- Using LiDAR point cloud data to visualize finer-resolution details and expand on the existing Blender visualization. The LiDAR citations note tiles of interest. Alternatively, .LAZ point clouds will be visualized using Potree or Innerscene tools for validation checks.<br>
- A comprehensive temporal analysis using openEO or similar time-series libraries will be used to expand the current temporal analysis. Additionally, further exposure to bath processing will be used for workflow optimization.<br>
- Understanding imputation and interpolation methods for NoData or bad pixels.<br>
- Explore additional pixel masking techniques for shadows and illumination angles.<br> 
- Understand correlation between temporal NDVI, Landsat temperature fluctuations, and fill sinks. 

## Data Citation

### Earth Engine Datasets
#### Dynamic World V1 Dataset
**Dataset**: [Dynamic World V1](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1#description)<br>
**Dataset Name**: dynamic_world_20260918_T10UDV.tif<br>
**Dataset Citation**: Brown, C.F., Brumby, S.P., Guzder-Williams, B. et al. Dynamic World, Near real-time global 10 m land use land cover mapping. Sci Data 9, 251 (2022). doi:10.1038/s41597-022-01307-4<br>
**Use License**: This dataset is licensed under CC-BY 4.0 and requires the following attribution: "This dataset is produced for the Dynamic World Project by Google in partnership with National Geographic Society and the World Resources Institute."
Contains modified Copernicus Sentinel data [2015-present].

#### Harmonized Sentinel-2 MSI Dataset
**Dataset**: [Harmonized Sentinel-2 MSI](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR_HARMONIZED#terms-of-use)<br>
**Dataset Name**: Multiple images from Harmonized Sentinel-2 MSI: MultiSpectral Instrument, Level-2A (SR), see EE filters and composites in data_cleaning.ipynb\EarthEngine Sentinel-2 & Dynamic World V1\Get Harmonized Sentinel-2 MSI Level-2A (SR).<br> 
**Dataset Citation**: European Union/ESA/Copernicus<br> 
**Use License**: Terms and Conditions of the Copernicus Sentinel Data

### OpenTopography Dataset
**Dataset**: [OpenTopography](https://portal.opentopography.org/result?id=rt1789275687841)<br>
**Dataset Name**: CA_MRDEM<br>
**Dataset Citation**: Natural Resources Canada (2025).  Medium Resolution Digital Elevation Model of Canada.  Distributed by OpenTopography. https://doi.org/10.5069/G9N8780J. Accessed 2026-09-13<br> 
**Use License**: Open Government Licence - Canada<br>



