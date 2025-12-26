# See Ice? Trends in Arctic Surface Air Temperature, Sea Temperature, and Ice Coverage in Relation to Global Warming

## Contributors:

🌊 Ashley Nguyen
🧊 Erin Dominguez

## Description

In this notebook, we will explore how the surface air temperature, sea temperature, and sea ice coverage in the Arctic region have progressed over the past decades. We will pull two data sources, one from the Copernicus Marine Service for the Arctic sea and ice surface temperature data, and the other from the National Snow and Ice Data Center for the surface air temperature data. By connecting and observing how each of these three atmospheric and cryospheric variables interconnect, we will provide a more nuanced understanding of how this vicious, positive feedback cycle is driving Arctic melting at an unprecedented rate.

The notebook is split into two parts to accomodate the memory limitations of jupyter notebooks and our two massive datasets. First, please read the surface_air_temp.ipynb file, which contains our scientific background. Then read the sea_ice_analyzed file, which contains our conclusion and statement of AI usage.

## Data Sources

[Surface Air Temperature:](https://nsidc.org/data/soac/near-surface-air-temperatures)
- This data is sourced by the National Snow and Ice Data Center and the NASA Modern-Era Retrospective Analysis for Research and Applications (MERRA) reanalysis project version 2. Surface air temperatures were measured 2 meters above the Earth’s surface and have been collected from multiple sources, including satellites, aircraft, balloon-borne instruments, and weather stations. This collection also consists of other meteorological variables, including air temperature at 2 meters, wind components, sea level pressure, surface pressure, and total precipitable water vapor.

[Sea Surface Temperature/Sea Ice Concentration:](https://data.marine.copernicus.eu/product/SEAICE_ARC_PHY_CLIMATE_L4_MY_011_016/description)
- The “Arctic Ocean - Sea and Ice Surface Temperature REPROCESSED” dataset is a spatial imagery dataset that contains daily, gap-free temperature maps of the Arctic Ocean surface, sea ice, and marginal ice zone data. This dataset is created by the Copernicus Marine Service and covers satellite observations from 1981 to 2024 with data products including sea surface temperature (SST) and sea ice surface temperature (IST). Since these satellite observations are in NetCDF files, they will be read using the netCDF4 library and processed using xarray.
