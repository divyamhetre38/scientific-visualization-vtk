# Scientific Visualization and Isocontour Extraction using VTK

## Overview

This project demonstrates scientific data visualization techniques using the Visualization Toolkit (VTK). The workflow includes loading volumetric datasets, extracting isocontours from scalar fields, generating 2D visualizations, and performing interactive 3D volume rendering.

The project provides insights into how scalar-valued scientific data can be analyzed and visualized through contour extraction and volume rendering techniques commonly used in computational science, medical imaging, and engineering simulations.

---

## Features

* Load and process VTK image datasets (`.vti`)
* Extract isocontours from scalar fields using interpolation-based contouring
* Generate 2D scalar-field visualizations with color mapping
* Perform interactive 3D volume rendering
* Apply opacity and color transfer functions for volumetric visualization
* Visualize pressure distributions and spatial patterns in scientific datasets

---

## Technologies Used

* Python
* VTK (Visualization Toolkit)
* NumPy

---
## Dataset

This project uses the Isabel hurricane dataset in VTK ImageData (.vti) format.

Due to dataset size and licensing considerations, the dataset is not included in this repository.

Users can obtain the dataset from the course resources or official VTK sample datasets and place it in the project directory before running the notebook.

---

## Project Components

### 1. Isocontour Extraction

Implemented contour extraction from scalar fields by identifying edge intersections and generating contour-line representations.

### 2. 2D Scientific Visualization

Visualized scalar-valued datasets using color mapping techniques to highlight variations in pressure distribution.

### 3. 3D Volume Rendering

Constructed volume-rendering pipelines using transfer functions to explore internal structures within volumetric datasets.

---

## Results

### Isocontour Visualization

Generated contour lines representing regions of equal scalar value.

### 2D Scalar Field Visualization

Produced color-mapped visualizations for analyzing pressure variations and spatial trends.

### 3D Volume Rendering

Rendered volumetric data interactively using opacity and color transfer functions to reveal internal features.

---

## Applications

* Scientific Computing
* Computational Fluid Dynamics (CFD)
* Medical Imaging
* Geospatial Visualization
* Engineering Simulations
* Data Visualization

---

## Author

-Divya Mhetre
-B.Tech, Chemical Engineering
-Indian Institute of Technology Kanpur
