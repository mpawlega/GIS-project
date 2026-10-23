![Project Banner](./assets/elevation_render.png)

# Remote Sensing Project
[Remote sensing data workflow and visualization using Environment Canada satellite data.] 

## About the Project

## Python Data Cleaning Workflow
### Corbel Spatial Geospatial Wheels Index
**GitHub**: [Corbel Spatial Wheels](https://github.com/corbel-spatial/geospatial-wheels-index)
### Earth Engine
### Data Load, Mask, and Cleaning

## Python Data Analysis Workflow
### Initial Statistical Analysis
### RandomForest and K-means 

## Blender Simulation
![Elevation Render](./assets/geometry_nodes.png)

## Future Work
Additional exploratory work investigated LiDAR and Landsat in the ROI; these are not included in the main analysis. Future expansions may include the following:
- Using LiDAR point cloud data to visualize finer-resolution details and expand on the existing Blender visualization. The LiDAR citations note tiles of interest. Alternatively, .LAZ point clouds will be visualized using Potree or Innerscene tools for validation checks.<br>
- A comprehensive temporal analysis using openEO or similar time-series libraries will be used to expand the current temporal analysis. Additionally, further exposure to bath processing will be used for workflow optimization.<br>
- Understanding imputation and interpolation methods for NoData or bad pixels.<br>
- Explore additional pixel masking techniques for shadows and illumination angles.<br> 
- Understand correlation between temporal NDVI, Landsat temperature fluctuations, and flow direction. 

## Data Citation

### Copernicus Sentinel 2 Dataset
**Dataset**: [Copernicus Browser](https://browser.dataspace.copernicus.eu/?zoom=13&lat=50.6407&lng=-128.10591&themeId=DEFAULT-THEME&visualizationUrl=U2FsdGVkX18h%2FcR5Do5UvGinMxbdtN4leg7QI2sHQ4%2BvQTDIZZyhCzuFrMWnNmgdbCq1FT32fkNAE5qb5IVIViayBzIDc7PhCwhZ%2BmdV727dfQYxt3q1ilfJ4kzAGaYD&datasetId=S2_L2A_CDAS&fromTime=2026-09-15T00%3A00%3A00.000Z&toTime=2026-09-15T23%3A59%3A59.999Z&layerId=2_FALSE_COLOR&demSource3D=%22MAPZEN%22&cloudCoverage=30&dateMode=SINGLE&panel=layers)<br>
**Dataset Citation**:  European Space Agency. (2026). Copernicus Sentinel-2 data 2026. Retrieved from the Copernicus Data Space Ecosystem Browser. Product ID: S2A_MSIL2A_20260918T191831_N0512_R056_T10UDV_20260919T014720.<br>
**Use License**:  Copernicus Free, Full, and Open Data Policy. Attribution: "Contains modified Copernicus Sentinel data 2026."

### Earth Engine Datasets
#### Dynamic World V1 Dataset
**Dataset**: [Dynamic World V1](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1#description)<br>
**Dataset Name**: dynamic_world_20260918_T10UDV.tif<br>
**Dataset Citation**: Brown, C.F., Brumby, S.P., Guzder-Williams, B. et al. Dynamic World, Near real-time global 10 m land use land cover mapping. Sci Data 9, 251 (2022). doi:10.1038/s41597-022-01307-4<br>
**Use License**: This dataset is licensed under CC-BY 4.0 and requires the following attribution: "This dataset is produced for the Dynamic World Project by Google in partnership with National Geographic Society and the World Resources Institute."
Contains modified Copernicus Sentinel data [2015-present].

#### Harmonized Sentinel-2 MSI Dataset
**Dataset**: [Harmonized Sentinel-2 MSI](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR_HARMONIZED#terms-of-use)<br>
**Dataset Name**: Harmonized Sentinel-2 MSI: MultiSpectral Instrument, Level-2A (SR)<br> 
**Dataset Citation**: European Union/ESA/Copernicus<br> 
**Use License**: Terms and Conditions of the Copernicus Sentinel Data

#### Landsat Dataset
**Dataset**: [USGS Landsat 9 Level 2, Collection 2, Tier 1](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC09_C02_T1_L2?_gl=1*k8hbmi*_up*MQ..*_ga*MTI0MTQzODAxMS4xNzkxNzUwNzk3*_ga_SM8HXJ53K2*czE3OTE3NTA3OTYkbzEkZzAkdDE3OTE3NTA3OTYkajYwJGwwJGgw#terms-of-use)<br>
**Dataset Name**: LC09_048026_20260915.tif<br>
**Dataset Citation**: Landsat-9 image courtesy of the U.S. Geological Survey (Asset: LC09_048026_20260915).<br>
**Use License**: Public Domain (U.S. Government Work). Attribution: "Landsat data resides in the public domain and may be used without copyright restriction. Credit courtesy of the U.S. Geological Survey."

### LiDAR Dataset
**Dataset**: [LidarBC](https://lidar.gov.bc.ca/pages/download-discovery)<br>
**Dataset Name(s)**: 
- bc_092g005_x1m_utm10_170714.tif<br>
- bc_092g005_x1m_utm10_170714.tif<br>
- bc_092g006_x1m_utm10_170714.tif<br>
- bc_092g015_x1m_utm10_170714.tif<br>
- bc_092g016_x1m_utm10_170714.tif<br>
- bc_092g025_xl1m_utm10_170713.tif<br>
- bc_092g026_xl1m_utm10_170713.tif<br>
- bc_092g035_xl1m_utm10_170713.tif<br>
- bc_092g036_xl1m_utm10_170713.tif<br>
- bc_092g045_xl1m_utm10_170713.tif<br>
- bc_092g046_xl1m_utm10_170713.tif<br>

**Dataset Citation**: Province of British Columbia. (2017). LidarBC Open LiDAR Data Portal: Map Tiles 092G (005, 006, 015, 016, 025, 026, 035, 036, 045, 046) [Data set]. GeoBC. https://lidar.gov.bc.ca/pages/download-discovery<br>
**Use License**: LidarBC data is published as Open Data under the Open Government Licence – British Columbia (OGL-BC). Contains information licensed under the Open Government Licence – British Columbia.

### OpenTopography Dataset
**Dataset**: [OpenTopography](https://portal.opentopography.org/result?id=rt1789275687841)<br>
**Dataset Name**: 
**Dataset Citation**: Natural Resources Canada (2025).  Medium Resolution Digital Elevation Model of Canada.  Distributed by OpenTopography. https://doi.org/10.5069/G9N8780J. Accessed 2026-09-13<br> 
**Use License**: Open Government Licence - Canada<br>



