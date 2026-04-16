# Image Processing

A comprehensive collection of image processing techniques implemented in Python, covering intensity transformations, filtering, edge detection, and advanced processing methods.

## Overview

This project contains implementations of various image processing algorithms using OpenCV, NumPy, and Matplotlib.

## Environment Setup

### Prerequisites
- Python 3.12.3
- Virtual environment (`.venv`)

### Installation

1. Activate the virtual environment:

2. Required packages:
- numpy 2.4.4
- opencv-python 4.13.0.92
- matplotlib 3.10.8
- scipy 1.17.1
- jupyter

## Project Structure

### Notebooks

#### Intensity Transformations
- Gamma correction (γ=0.5, γ=2.0) and contrast stretching on runway.png
- Gamma correction in L*a*b* color space
- Custom histogram equalization implementation
- Otsu thresholding and selective histogram equalization

#### Filtering Techniques
- Gaussian filtering (manual 5×5 and 51×51 kernels)
- Derivative of Gaussian for edge detection
- Noise filtering (Gaussian smoothing and median filtering)
- Image sharpening techniques
- Bilateral filtering (manual implementation + OpenCV comparison)

#### Image Processing Operations
- Image zooming with nearest-neighbor and bilinear interpolation

#### Theoretical Analysis
- Spatial filtering and frequency response relationship
- Illumination correction using homomorphic filtering


## Key Features

### Implemented Algorithms

1. **Intensity Transformations**
   - Gamma correction (power-law transformations)
   - Contrast stretching (piecewise linear)
   - L*a*b* color space processing

2. **Histogram Processing**
   - Custom histogram equalization
   - Otsu's thresholding
   - Selective histogram equalization

3. **Spatial Filtering**
   - Gaussian filtering (manual and OpenCV)
   - Median filtering
   - Bilateral filtering (edge-preserving)
   - Derivative of Gaussian

4. **Edge Detection & Enhancement**
   - Sobel operator
   - Laplacian
   - Unsharp masking
   - Image sharpening

5. **Geometric Operations**
   - Image zooming/scaling
   - Nearest-neighbor interpolation
   - Bilinear interpolation

6. **Advanced Techniques**
   - Homomorphic filtering (theory)
   - Frequency domain analysis
   - Convolution theorem applications

## Usage

### Running Notebooks

1. Start Jupyter:
```bash
jupyter notebook
```

2. Open any `.ipynb` file and run cells sequentially

3. All notebooks are configured to use the `.venv` kernel (Python 3.12.3)

## Results

Each notebook includes:
- Implementation code
- Visualizations (before/after comparisons)
- Parameter analysis
- Performance metrics
