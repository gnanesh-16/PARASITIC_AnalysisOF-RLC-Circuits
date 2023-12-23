# **VLSI** Circuit Analysis using **Machine** **Learning** for RLC **Parasitic** Estimation in Circuits

This repository contains code and resources related to the application of machine learning algorithms for accurate estimation of parasitic resistance (R), parasitic capacitance (C), and power consumption in Very Large Scale Integration (VLSI) adder circuits. The goal is to address the challenges posed by traditional methods when analyzing the impact of parasitic elements on circuit performance.

## Overview
VLSI circuits often face estimation errors when conventional techniques are used to analyze parasitic effects such as R, C, and power consumption in adder circuits with unique architectures. To tackle this, the project explores the implementation of machine learning algorithms for more precise and tailored estimations.

# PARASITIC_AnalysisOF-RLC-Circuits
The prevailing techniques for estimating power, RParasitic R,
C, and Power Estimation Analysis for Adder Family
Circuits VLSI circuits rely on intricate mathematical models, often resulting in inaccuracies when applied to unique circuit architectures. Adders, fundamental to circuit design, necessitate precise analysis considering factors like parasitic capacitance (C), resistance (R), power consumption, and maximum operating current. Addressing these challenges demands specific and accurate methodologies.

## Methodology

### Data Collection
- Various adder circuits were utilized to collect a dataset.
- Parameters including R, C, and power were extracted from individual circuit layouts.

### Machine Learning Models
- **Linear Regression:** Used to create a power estimation model with an exceptional 99.99% accuracy in model fitting.
- **Estimation of R and C:** The same regression method resulted in observed accuracies of 73.17% and 90.98%, respectively, when other parameters were maintained as independent variables.
- **K-means Clustering:** Employed for grouping R, L, C, and power within ranges spanning minimum to maximum values, achieving 100% accuracy with 8 clusters.

## Repository Structure

- `code/`: Contains code implementation for data collection, preprocessing, and machine learning models.
- `datasets/`: Includes datasets extracted from various adder circuits for analysis.
- `results/`: Stores results obtained from different machine learning models and analyses.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/gnanesh-16/PARASITIC_AnalysisOF-RLC-Circuits.git
    ```

2. Navigate to the specific folders (`code/`, `datasets/`, `results/`) to access the respective resources and code implementations.

## Requirements

- Python 3.x
- Libraries: NumPy, Pandas, Scikit-learn, Matplotlib
