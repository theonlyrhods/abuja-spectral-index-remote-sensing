# Abuja Spectral Index & Mineral Ratio Remote Sensing Analysis

## Project Overview

This project presents a multispectral remote sensing analysis of Abuja, Federal Capital Territory (FCT), Nigeria using Landsat 9 imagery. Spectral indices and mineral band ratios were computed to analyze vegetation cover, surface water, built-up areas, and mineral-related surface characteristics.

The analysis was conducted using raster processing techniques in ArcGIS 10.2.2.

---

## Study Area

- Location: Abuja, FCT, Nigeria
- Coordinate System: UTM Zone 32N
- Administrative Boundary: Abuja State shapefile

---

## Data Sources

Satellite Imagery:
- Satellite: Landsat 9
- Year: 2022
- Path: 189
- Row: 054
- Bands Used: Band 1 – Band 11

Software:
- ArcGIS 10.2.2

---

## Methodology

### 1. Image Preparation

- Landsat 9 imagery (Bands 1–11) was loaded into ArcGIS.
- The Abuja boundary shapefile was used to define the study extent.
- Bands were organized for raster analysis and ratio computation.

---

## Spectral Index Computation

Raster Calculator in ArcGIS was used to compute the following indices:

### NDVI (Normalized Difference Vegetation Index)

NDVI = (Band 5 − Band 4) / (Band 5 + Band 4)

- Band 5 = Near Infrared (NIR)
- Band 4 = Red

Used to assess vegetation density and spatial distribution.

---

### NDWI (Normalized Difference Water Index)

NDWI was computed to detect surface water bodies and moisture distribution using appropriate spectral band combinations.

---

### NDBI (Normalized Difference Built-up Index)

NDBI was calculated to identify built-up and urbanized surfaces within Abuja.

---

## Mineral Band Ratio Analysis

Mineral-sensitive band ratios were computed to enhance surface reflectance characteristics associated with specific mineral types. The outputs were classified into relative low and high reflectance values for visualization.

### Clay Mineral Ratio

A clay-sensitive band ratio was computed using shortwave infrared bands. The resulting raster highlighted areas of relatively higher and lower reflectance associated with clay-bearing materials.

### Ferrous Mineral Ratio

A ferrous mineral ratio was calculated to enhance surface reflectance variations potentially associated with ferrous-bearing materials.

### Iron Oxide Ratio

An iron oxide ratio was computed to detect relative reflectance differences associated with ferric oxide surfaces.

All ratio outputs were symbolized using graduated color ramps to represent low and high reflectance values.
---

## Output Products

The project generated:

- NDVI vegetation distribution map
- NDWI water detection map
- NDBI built-up area map
- Clay mineral ratio map
- Ferrous mineral ratio map
- Iron oxide ratio map
- Final cartographic layouts exported from ArcGIS

(Map outputs available in the /maps folder.)

---

## Technical Skills Demonstrated

- Multispectral raster processing
- Spectral band manipulation
- Mineral band ratio computation
- Environmental index analysis
- Raster Calculator operations
- Spatial referencing (UTM Zone 32N)
- Thematic map classification
- Cartographic layout design

---

## Project Relevance

This project demonstrates applied remote sensing techniques for environmental monitoring and surface mineral detection using multispectral satellite imagery. It reflects practical experience in both environmental and geological remote sensing workflows.

---

## Limitations

This analysis focused on spectral ratio generation and visualization. Detailed geological validation and ground-truth verification were beyond the scope of this project.
