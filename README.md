# Multiprocessing Data Analysis Project

This project demonstrates the use of multiprocessing in Python for parameter distribution analysis and bootstrapping techniques. It includes two main problems: Parameter Distributions and Bootstrapping.

## Table of Contents
- [Problem 1: Parameter Distributions](#problem-1-parameter-distributions)
- [Problem 2: Bootstrapping](#problem-2-bootstrapping)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Problem 1: Parameter Distributions

This section focuses on generating fake linear data, adding noise, and analyzing the distribution of fitted parameters using parallel processing.

### Key features:
- Generate synthetic linear data with noise
- Fit data using `curve_fit`
- Parallel processing to perform multiple fits
- Histogram visualization of fitted parameters

## Problem 2: Bootstrapping

This section demonstrates bootstrapping techniques to estimate errors on means, particularly for non-Gaussian distributions.

### Key features:
- Load and process astronomical data (M67 star cluster)
- Calculate mean parallax and standard deviation
- Implement bootstrapping to estimate error on the mean
- Use parallelization to create multiple bootstrapped datasets

## Installation

```bash
git clone https://github.com/NDelan/Parallel-Data-Simulation-and-Statistical-Analysis.git
cd Multiprocessing_Bootstrap

## Dependencies

- NumPy
- Matplotlib
- SciPy
- multiprocess

Make sure to install these dependencies using pip:

```bash
pip install numpy matplotlib scipy multiprocess
