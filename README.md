# Earth Observation Sources

I am aggregating a list of Earth Observation sources and pertinent info, feel free to contribute.

## Free/Open Satellite Data

| Source Name | URL | Data Type | Resolution | License | Cost | API Access | Notes |
|-------------|-----|-----------|------------|---------|------|------------|-------|
| Sentinel Hub | [link](https://scihub.copernicus.eu) | Satellite (Optical, SAR) | 10–60m | Open (Copernicus) | Free | Yes | EO Browser and API |
| Copernicus Data Space | [link](https://dataspace.copernicus.eu) | Satellite (Optical, SAR) | 10–60m | Open (Copernicus) | Free | Yes | New platform replacing SciHub |
| Landsat USGS EarthExplorer | [link](https://earthexplorer.usgs.gov) | Imagery, Elevation, LiDAR | 30m, LiDAR varies | Public Domain | Free | Limited | Historic archive, bulk tools |
| MODIS (NASA) | [link](https://modis.gsfc.nasa.gov) | Satellite (Optical, Thermal) | 250m–1km | Public Domain | Free | Yes | Daily coverage, climate data |
| VIIRS | [link](https://www.earthdata.nasa.gov/sensors/viirs) | Satellite (Optical, Thermal) | 375m–750m | Public Domain | Free | Yes | Day/night imagery, NOAA/NASA |
| NASA Earthdata/EOSDIS | [link](https://earthdata.nasa.gov) | Multiple (Satellite, Airborne) | Varies | Public Domain | Free | Yes | Portal for all NASA Earth science data |
| JAXA Global ALOS | [link](https://www.eorc.jaxa.jp/ALOS/en/) | Satellite (Optical, SAR) | 10–30m | Open (registration) | Free for research | Limited | Japanese satellite data |

## Commercial Optical Satellites

| Source Name | URL | Data Type | Resolution | License | Cost | API Access | Notes |
|-------------|-----|-----------|------------|---------|------|------------|-------|
| Maxar | [link](https://www.maxar.com) | Satellite (Optical) & DEM | 0.3–0.5m | Commercial | $25–$50/sqkm | Yes | Global coverage |
| Airbus | [link](https://www.airbus.com/en/products-services/space/earth-observation/satellite-imagery) | Satellite (Optical) & DEM | 0.3–5m | Commercial | $5–25/sqkm | Yes | Global DEM & Imagery |
| Planet | [link](https://www.planet.com) | Satellite (Optical) | 0.5–5m | Commercial | $6–$40/sqkm | Yes | Global, excellent platform |
| Blacksky | [link](https://www.blacksky.com) | Satellite (Optical) | 0.35–1m | Commercial | $25/sqkm | Yes | Global, new 35cm archive |
| Satellogic | [link](https://www.satellogic.com) | Satellite (Optical) | 0.7–1m | Commercial | $8–$18/sqkm | Yes | Global coverage |
| Orora Tech | [link](https://www.ororatech.com) | Satellite (Thermal) | 80m | Commercial | $25/sqkm | Yes | Wildfire detection |
| Muon Space | [link](https://www.muonspace.com) | Satellite (Firesat) | 5m | Commercial | n/a | Yes | Environmental monitoring |

## Commercial SAR Satellites

| Source Name | URL | Data Type | Resolution | License | Cost | API Access | Notes |
|-------------|-----|-----------|------------|---------|------|------------|-------|
| Umbra | [link](https://www.umbra.space) | Satellite (SAR) | 25cm–1m | CC 4.0 | [varies/sqkm](https://umbra.space/pricing/) | Yes | High-resolution SAR |
| Capella Space | [link](https://www.capellaspace.com) | Satellite (SAR) | 0.5m | Commercial | $4000–6000/image | Yes | High-resolution SAR |
| Iceye | [link](https://www.iceye.com) | Satellite (SAR) | 25cm–1m | Commercial | $5000/image | Yes | Global coverage |
| Synspective | [link](https://synspective.com) | Satellite (SAR) | 1–3m | Commercial | Varies | Yes | SAR provider |

## Commercial Hyperspectral Satellites

| Source Name | URL | Data Type | Resolution | License | Cost | API Access | Notes |
|-------------|-----|-----------|------------|---------|------|------------|-------|
| Pixxel | [link](https://www.pixxel.space) | Satellite (Hyperspectral) | 5m | Commercial | $150/seat/month | Yes | Global coverage |
| Wyvern | [link](https://www.wyvern.space) | Satellite (Hyperspectral) | 5.3m | Commercial | $230/seat/year | Yes | Global coverage |
| Orbital Sidekick | [link](https://www.orbitalsidekick.com) | Satellite (Hyperspectral) | 8m | Commercial | n/a | Yes | Global coverage |

## Elevation & LiDAR Data

| Source Name | URL | Data Type | Resolution | License | Cost | API Access | Notes |
|-------------|-----|-----------|------------|---------|------|------------|-------|
| OpenTopography | [link](https://opentopography.org) | LiDAR, DEM | 0.5–5m | Mostly open | Free | Yes | Regional coverage, custom filters |
| USGS National Map | [link](https://apps.nationalmap.gov) | Elevation, Hydro, Vector | 1–10m | Public Domain | Free | Yes | Great US coverage |
| SRTM | [link](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-shuttle-radar-topography-mission-srtm) | Elevation (DEM) | 30m (US), 90m (global) | Public Domain | Free | Yes | Global elevation from 2000 |

## Vector Data

| Source Name | URL | Data Type | Resolution | License | Cost | API Access | Notes |
|-------------|-----|-----------|------------|---------|------|------------|-------|
| OpenStreetMap | [link](https://www.openstreetmap.org) | Vector | N/A | ODbL | Free | Yes | Global, editable |
| Overture Maps | [link](https://overturemaps.org) | Vector (Places, Roads) | N/A | Open | Free | Yes | Backed by Meta, AWS, Microsoft, TomTom |

## Data Platforms & APIs

| Source Name | URL | Data Type | Resolution | License | Cost | API Access | Notes |
|-------------|-----|-----------|------------|---------|------|------------|-------|
| Google Earth Engine | [link](https://earthengine.google.com) | Analysis platform | Varies | Free for research/edu | Free (non-commercial) | Yes | Petabytes of data, cloud processing |
| Microsoft Planetary Computer | [link](https://planetarycomputer.microsoft.com) | Multiple datasets | Varies | Varies | Free | Yes | Catalog with Sentinel, Landsat, more |
| AWS Open Data Registry | [link](https://registry.opendata.aws) | Multiple datasets | Varies | Open | Free (egress fees) | Yes | Hosts Sentinel, Landsat, NAIP |
| Element 84 Earth Search | [link](https://www.element84.com/earth-search) | Search API | N/A | Open | Free | Yes | STAC API for satellite imagery |
| Radiant Earth MLHub | [link](https://mlhub.earth) | ML-ready datasets | Varies | Varies | Free | Yes | Training data for ML applications |

---

**Contributing:** Please submit pull requests or issues to suggest additions or corrections!
