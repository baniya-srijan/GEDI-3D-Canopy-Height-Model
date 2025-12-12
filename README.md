# GEDI-3D-Canopy-Height-Model
Canopy Height model using GEDI L2A Data
This project focuses on extracting and visualizing 3D forest canopy height using NASA GEDI L2A spaceborne LiDAR data.

Overview
NASA’s Global Ecosystem Dynamics Investigation (GEDI) provides waveform-derived relative height metrics that describe vegetation structure from ground to canopy top.
In this project, GEDI L2A products are processed to generate 3D visualizations of canopy height profiles, enabling structural interpretation of forested areas.

The work emphasizes:

Correct handling of GEDI L2A relative height (RH) metrics

Spatial consistency and filtering of footprint-level data

Clear visualization of vertical canopy structure

Data
Source: NASA GEDI L2A products
Metrics used: Relative height percentiles
Coordinate System: UTM 15N

Workflow
1. Reading and filtering GEDI L2A data
2. Extracting rh and necesary metrics
3. Handling outliers and transforming spatial coordinates to a common CRS
4. Generating 3D visualizations to examine canopy profiles and variations

Visual Results

The repository includes representative figures showing:
1. Oblique 3D views of canopy height distribution
2. Vertical profile views highlighting ground-to-canopy separation

Acknowledgements

This work was completed under the guidance of Dr. Joydeep Bhattacharjee and Grant Erbelding.

