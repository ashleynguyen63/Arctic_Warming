# Final project proposal

**See Ice? Trends in sea ice coverage, sea surface temperature, and global warming**

Team: Ashley Nguyen, Erin Dominguez

Description: Sea ice in the Arctic is both a key climate indicator and feedback mechanism for global warming; melting sea ice reduces the albedo of the Arctic, allowing the ocean to absorb more heat and accelerate global warming. Our project will attempt to characterize the speed and distribution of the melting sea ice, and understand its relationship to salinity and the Atlantic Meridional Overturning Circulation and global mean temperatures. 

Description of Dataset: The “Arctic Ocean - Sea and Ice Surface Temperature REPROCESSED” dataset is a spatial imagery dataset that contains daily, gap-free temperature maps of the Arctic Ocean surface, sea ice, and marginal ice zone data. This dataset is created by the Copernicus Marine Service and covers satellite observations from 1981 to 2024 with data products including sea surface temperature (SST) and sea ice surface temperature (IST). Since these satellite observations are in NetCDF files, they will be read using the netCDF4 library and processed using xarray.

Link of Dataset: https://data.marine.copernicus.eu/product/SEAICE_ARC_PHY_CLIMATE_L4_MY_011_016/description




Questions & Analysis Performed:

How has the sea ice extent coverage in the Arctic changed between 1981 and 2024?
- Analysis of combined satellite imagery to assess sea ice coverage (similar to NDVI analysis in module 3)

How does melting in Arctic sea ice contribute to the weakening of the Atlantic Meridional Overturning Circulation (AMOC)?
- Analysis may consider looking at the satellite imagery for the temporal and spatial changes in sea ice melting and combining it with metadata that contain information about that particular region’s sea surface salinity, salinity anomaly, sea ice melt, and freshwater.

To what extent are sea surface temperatures correlated with annual sea surface temperatures in the arctic?
- Graph mean sea surface temperatures against ice surface temperature averages and coverage and determine the strength of the correlation via linear regression
- Perform the above analysis for multiple regions as well as the whole arctic to see whether the pattern varies by region


