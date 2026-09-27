# UrbaSustain — Agricultural & Urban Monitoring in Sousse

An end-to-end geospatial intelligence project for monitoring agricultural land change and urban expansion in the Sousse Governorate, Tunisia, using Sentinel-2 satellite imagery, GIS, remote sensing, and machine learning.

# Overview

Agricultural land and urban areas are constantly evolving, making continuous monitoring essential for sustainable land-use planning.

This project explores the evolution of agricultural land cover and urban expansion in the Sousse Governorate using multi-temporal Sentinel-2 imagery and machine learning techniques.

The project combines remote sensing analysis, geospatial processing, machine learning, change detection, and interactive visualization into a unified workflow.

The final results are integrated into **UrbaSustain**, an interactive geospatial dashboard designed to make the generated analyses and maps accessible through a single interface.

# Objectives

The main objectives of the project are to:

* Monitor agricultural land-cover changes over time
* Classify agricultural land using satellite imagery and machine learning
* Identify and analyze urban expansion
* Detect significant land-cover changes
* Model areas associated with urban expansion
* Analyze the relationship between agricultural change and urban growth
* Provide interactive geospatial visualizations for decision support

# Project Workflow

```text
Sentinel-2 Imagery
        │
        ▼
Data Preprocessing
        │
        ▼
Spectral & Temporal Features
        │
        ├──────────────────────────┐
        ▼                          ▼
Agricultural Classification   Urban Classification
        │                          │
        └──────────────┬───────────┘
                       ▼
                Change Detection
                       │
                       ▼
             Urban Expansion Analysis
                       │
                       ▼
              Spatial / Land Pressure
                       │
                       ▼
                UrbaSustain Dashboard
```

# Technologies

## Geospatial & Remote Sensing

* Google Earth Engine
* Sentinel-2
* Remote sensing
* NDVI and other spectral indices

## Machine Learning

* Random Forest
* 1D Convolutional Neural Network
* XGBoost
* Model evaluation and validation

## Development

* Python
* JavaScript
* React
* Vite
* Leaflet
* Chart.js

# Main Components

## Agricultural Classification

A machine learning workflow was developed to classify agricultural land using Sentinel-2-derived features and institutional ground-truth data.

### Urban Classification

Satellite-derived information was used to identify built-up areas and characterize urban development.

### Change Detection

A temporal change-detection workflow was developed to identify agricultural land-cover changes over time.

### Urban Expansion Suitability

Machine learning was also used to investigate the spatial characteristics associated with urban expansion and identify areas with higher expansion suitability.

## UrbaSustain Dashboard

The different outputs are brought together in UrbaSustain, an interactive web-based geospatial platform.

The dashboard combines agricultural and urban analyses within a common cartographic environment, allowing users to explore spatial patterns and statistics interactively.

The dashboard includes:

* Interactive maps
* Agricultural land-cover layers
* Urban classification layers
* Urban expansion maps
* Change-detection results
* Administrative delegation boundaries
* Spatial statistics
* Infrastructure and green-space layers

The dashboard was implemented using React, Vite, Leaflet, Tailwind CSS, Chart.js, and geospatial visualization libraries.

## Key Results

| Analysis                    |          Result |
| --------------------------- | --------------: |
| Agricultural classification |  81.6% accuracy |
| Urban classification        |  92.4% accuracy |
| Change detection            | 0.9685 F1-score |
| Urban expansion suitability |  84.4% accuracy |

These results demonstrate the potential of combining satellite imagery, machine learning, and GIS for large-scale land monitoring.


## Data

Due to data size, licensing, and institutional restrictions, the original datasets are not included in this repository.

The repository instead provides the processing workflows, scripts, documentation, and reproducibility guidelines required to understand and reproduce the methodology with appropriate datasets.

## Internship Context

This project was developed during my summer internship at ST2I Groupe Studi.

The internship provided an opportunity to apply academic knowledge in GIS, remote sensing, machine learning, and geospatial analysis to a real-world environmental and urban planning problem.

## Acknowledgements

Special thanks to ST2I Groupe Studi and to Mr. Hatem Ben Hassine for the guidance and support throughout this internship.

Thanks also to Jamila Abidi for the collaboration and for sharing this experience throughout the project.

## Author

**Farah Ben Choug**

Engineering Student | GIS | Remote Sensing | Machine Learning | Geospatial AI

## Keywords

GIS / Remote Sensing / Machine Learning / Geospatial / AI / Earth Observation / Sentinel-2 / Google Earth Engine / Urban Growth / Agricultural Monitoring / Sousse Tunisia
