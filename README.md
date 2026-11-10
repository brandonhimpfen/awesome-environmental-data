# Awesome Environmental Data [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for environmental data science, satellite Earth observation feeds, climate reanalysis archives, atmospheric telemetry APIs, biodiversity databases, and oceanographic data pipelines.

Environmental data science integrates remote sensing, climate modeling, in-situ sensor networks, and spatial analysis to monitor terrestrial ecosystems, atmospheric conditions, and global climate trends. By leveraging open data standards, Cloud-Optimized GeoTIFFs (COG), SpatioTemporal Asset Catalogs (STAC), and netCDF multi-dimensional arrays, researchers and engineers can model land-use change, track air quality, process oceanic observations, and evaluate climate impacts. This list is intended for environmental data scientists, remote sensing specialists, climate analysts, GIS software engineers, and conservation researchers.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Earth Observation & Satellite Feeds](#earth-observation--satellite-feeds)
- [Climate & Reanalysis Archives](#climate--reanalysis-archives)
- [Terrestrial & Biodiversity Datasets](#terrestrial--biodiversity-datasets)
- [Atmospheric & Oceanographic Telemetry](#atmospheric--oceanographic-telemetry)
  - [Air Quality & Atmospheric Science](#air-quality--atmospheric-science)
  - [Oceanography & Marine Telemetry](#oceanography--marine-telemetry)
- [Data Processing Toolkits & APIs](#data-processing-toolkits--apis)
- [Related Awesome Lists](#related-awesome-lists)

## Earth Observation & Satellite Feeds

Open access satellite mission archives, STAC catalogs, and cloud-native imagery repositories.

- [NASA Earthdata](https://www.earthdata.nasa.gov/) — Centralized portal granting open access to EOSDIS satellite observations, land products, and remote sensing imagery.
- [Copernicus Data Space Ecosystem](https://dataspace.copernicus.eu/) — Open access platform providing Sentinel satellite imagery, radar datasets, and Earth observation products.
- [Earth Search by Element 84](https://earth-search.aws.element84.com/) — SpatioTemporal Asset Catalog (STAC) API querying public AWS archives of Sentinel-2 and Landsat imagery.
- [Google Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets) — Multi-petabyte analysis-ready repository of satellite imagery and geospatial datasets.
- [OpenLandMap](https://openlandmap.org/) — Global environmental data platform providing high-resolution spatial layers derived from machine learning and remote sensing.

## Climate & Reanalysis Archives

Historical climate observations, gridded reanalysis models, and global circulation outputs.

- [ECMWF ERA5 Reanalysis](https://www.ecmwF.int/en/forecasts/dataset/ecmwf-reanalysis-5) — Global atmospheric reanalysis dataset covering historical climate observations from 1940 to the present.
- [NOAA NCEI Climate Data Online](https://www.ncdc.noaa.gov/cdo-web/) — Access to global historical weather station summaries, temperature anomalies, and precipitation records.
- [CHIRPS (UCSB Climate Hazards Group)](https://www.chc.ucsb.edu/data/chirps) — Quasi-global rainfall dataset combining satellite imagery with in-situ station data for trend analysis.
- [CMIP6 (WCRP)](https://pcmdi.llnl.gov/CMIP6/) — Coupled Model Intercomparison Project Phase 6 repository hosting global climate projection scenarios.

## Terrestrial & Biodiversity Datasets

Global species occurrence networks, forest cover monitoring, and soil composition catalogs.

- [GBIF (Global Biodiversity Information Facility)](https://www.gbif.org/) — International open-data network providing access to species occurrence records worldwide.
- [Global Forest Watch Data Portal](https://data.globalforestwatch.org/) — Open datasets for near-real-time tree cover loss, land-use change, and deforestation alerts.
- [SoilGrids](https://www.isric.org/explore/soilgrids) — Machine-learning generated global maps of soil chemical and physical properties at 250m resolution.
- [iNaturalist Open Data](https://www.inaturalist.org/pages/open_data) — Open research-grade observations and taxonomy datasets contributed by global citizen science networks.

## Atmospheric & Oceanographic Telemetry

Sensor networks, buoy telemetry, and global atmospheric composition pipelines.

### Air Quality & Atmospheric Science

- [OpenAQ](https://openaq.org/) — Open-source global real-time and historical air quality data platform aggregating station data across nations.
- [Copernicus Atmosphere Monitoring Service (CAMS)](https://atmosphere.copernicus.eu/) — Continuous atmospheric composition forecasts, aerosol tracking, and greenhouse gas estimates.

### Oceanography & Marine Telemetry

- [Argo Float Program](https://argo.ucsd.edu/) — Global array of autonomous profiling floats delivering ocean temperature, salinity, and biogeochemical profile data.
- [EMODnet (European Marine Observation and Data Network)](https://emodnet.ec.europa.eu/) — Consortium collecting marine environmental data, seabed mapping, and bathymetry archives.

## Data Processing Toolkits & APIs

Open-source Python and R packages for handling multi-dimensional gridded arrays and spatial rasters.

- [xarray](https://github.com/pydata/xarray) — N-dimensional array package providing labeled dimensions, coordinates, and netCDF I/O integrations.
- [rioxarray](https://github.com/corteva/rioxarray) — Geospatial extension for xarray using Rasterio to handle coordinate reference systems and GeoTIFFs.
- [pystac](https://github.com/stac-utils/pystac) — Python library for working with SpatioTemporal Asset Catalog (STAC) metadata specifications.
- [rnaturalearth](https://github.com/ropensci/rnaturalearth) — R package for interacting with Natural Earth map data layers programmatically.

## Related Awesome Lists

- [Awesome Renewable Energy](https://github.com/brandonhimpfen/awesome-renewable-energy) — Solar PV modeling, wind assessment, battery storage frameworks, and smart grids.
- [Awesome Circular Economy](https://github.com/brandonhimpfen/awesome-circular-economy) — Material flow analysis, life cycle assessment, and eco-design toolkits.
- [Awesome Open Data](https://github.com/brandonhimpfen/awesome-open-data) — Public datasets, environmental spatial layers, and open scientific data portals.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Best practices, licensing standards, and community governance for open repositories.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

