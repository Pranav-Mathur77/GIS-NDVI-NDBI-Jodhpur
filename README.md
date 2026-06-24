# GIS-Based Assessment of Vegetation Density and Built-up Surface Distribution in Jodhpur City

## Project Overview

This project applies Remote Sensing and Geographic Information System (GIS) techniques to analyze vegetation density and built-up surface distribution within Jodhpur City, Rajasthan, India.

Using Sentinel-2 multispectral satellite imagery, Normalized Difference Vegetation Index (NDVI) and Normalized Difference Built-up Index (NDBI) were generated and classified to identify vegetation cover and urban surface density patterns.

The project was developed using QGIS and demonstrates the application of geospatial analysis for urban planning, environmental monitoring, and land-use assessment.

---

## Study Area

**Location:** Jodhpur City, Rajasthan, India

**Geographic Extent**

- Latitude: 26.22°N – 26.40°N
- Longitude: 72.90°E – 73.15°E

**Projection**

- WGS 84 / UTM Zone 43N
- EPSG:32643

---

## Objectives

- Generate a Vegetation Density Map using NDVI.
- Generate a Built-up Surface Density Map using NDBI.
- Classify vegetation into density categories.
- Classify built-up areas into density categories.
- Calculate area and percentage distribution of each class.
- Assess spatial patterns of urban development and vegetation cover.

---

## Data Used

| Dataset | Source |
|----------|----------|
| Sentinel-2 MSI Imagery | Copernicus Open Access Hub |
| Jodhpur Administrative Boundary | GIS Boundary Dataset |

### Spatial Resolution

20 meters

### Acquisition Year

2026

---

## Software Used

- QGIS 3.40
- Sentinel-2 MSI Imagery
- GIS & Remote Sensing Techniques

---

## Methodology

### Vegetation Density Mapping (NDVI)

1. Download Sentinel-2 imagery
2. Clip imagery to Jodhpur boundary
3. Calculate NDVI
4. Reclassify NDVI values
5. Generate Vegetation Density Map
6. Calculate area statistics

### Built-up Surface Mapping (NDBI)

1. Calculate NDBI
2. Reclassify NDBI values
3. Generate Built-up Density Map
4. Convert raster to vector
5. Dissolve classes
6. Calculate area and percentage

---

## Classification Scheme

### NDVI Vegetation Classes

| Class | Description |
|---------|---------|
| Built-up / Bare Land | Very Low Vegetation |
| Sparse Vegetation | Low Vegetation Density |
| Moderate Vegetation | Moderate Vegetation Density |
| Dense Vegetation | High Vegetation Density |

### NDBI Built-up Classes

| Class | Description |
|---------|---------|
| Water / Non-built-up | Lowest Built-up Presence |
| Low Built-up | Low Urban Density |
| Moderate Built-up | Moderate Urban Density |
| High Built-up | Dense Urban Surface |

---

# Maps

## 1. Vegetation Density Map

![Vegetation Density Map](Maps/NDVI%20Jodhpur%20Layout.png)


This map represents vegetation distribution across Jodhpur City using NDVI-based classification.

---

## 2. Built-up Surface Density Map (NDBI)

![Built-up Surface Density Map](Maps/Built-up%20Surface%20Density%20Map%20(NDBI).png)

This map illustrates urban surface density and built-up land distribution derived from NDBI classification.

---

## Project Report

Detailed methodology, classification process, area statistics, and interpretation are available in:

`Report/Jodhpur NDVI NDBI Project Report.pdf`

---

## Key Findings

### Vegetation Density

- Sparse vegetation dominates most of the study area.
- Dense vegetation is concentrated around parks, green belts, and agricultural zones.
- The semi-arid nature of Jodhpur is reflected in the vegetation distribution pattern.

### Built-up Density

- Moderate built-up density occupies the largest portion of the urban area.
- High built-up density zones are concentrated around developed urban centers.
- NDBI effectively highlights urban expansion patterns across the city.

---

## Applications

- Urban Planning
- Land Use Assessment
- Environmental Monitoring
- Sustainable City Development
- GIS Portfolio Demonstration

---

## Repository Structure

```
GIS-NDVI-NDBI-Jodhpur
│
├── Maps
│   ├── NDVI Jodhpur Layout.png
│   └── Built-up Surface Density Map (NDBI).png
│
├── Report
│   └── Jodhpur NDVI NDBI Project Report.pdf
│
├── LICENSE
└── README.md
```

---

## Author

**Pranav Mathur**

GIS | Remote Sensing | Environmental Analysis

Jodhpur, Rajasthan, India

---

## License

This project is licensed under the MIT License.
