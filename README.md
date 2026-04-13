# 1D Batch State Estimation with Odometry and Range Measurements
This repository implements a 1D batch state estimation pipeline using odometry and range measurements.
## Overview
The project estimates the position of a robot moving along a one-dimensional track. The estimator combines noisy odometry and range observations in a batch least-squares formulation. The implementation also includes uncertainty analysis, sparsity visualization, and RTS smoothing.
## Method
The implementation includes:
- Linear Gaussian motion and observation models
- Batch least-squares formulation
- Sparse tridiagonal system construction
- RTS smoother for state estimation
- Error histogram and uncertainty visualization
- Sparsity pattern analysis of the normal equations
## Files
- `batch_state_estimation_1d.py`: main implementation
- `requirements.txt`: Python dependencies
- `.gitignore`: excludes datasets, figures, and cache files
## Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
