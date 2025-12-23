# Seismic Image Processing for Salt Dome Boundary Enhancement

This project demonstrates a Python-based workflow for enhancing structural boundaries associated with salt domes in seismic section images using classical image-processing techniques.

## Overview
The workflow applies amplitude normalization, adaptive histogram equalization (CLAHE), and gradient-based edge detection to enhance high-gradient structural features in a seismic image. Thresholding and connected-component filtering are used to suppress noise and highlight potential salt-related boundaries. The results are visualized through interpretation overlays.

## Methods
- Grayscale normalization and amplitude balancing
- Adaptive histogram equalization (CLAHE)
- Gradient-based edge detection (Sobel operator)
- Threshold tuning and connected-component filtering
- Interpretation overlay generation

## Tools & Libraries
- Python
- OpenCV
- NumPy
- Matplotlib

## Data
The seismic image used in this project is a publicly available example seismic section. Raw data are not redistributed in this repository.

## Purpose
This project is intended as a technical demonstration of seismic image enhancement and signal-processing concepts and does not represent a full geological interpretation or automated salt delineation.

## Example Results
See the `results/` directory for processed images and boundary-enhancement overlays.
