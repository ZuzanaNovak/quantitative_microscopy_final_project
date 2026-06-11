# Quantitative Microscopy Final Project

This repository contains the final project for the Quantitative Microscopy course. 

## Project Overview

The main goal of this project is to evaluate the performance of Cellpose segmentation and use the extracted cell/nuclei features to explore biological differences between neoplastic and normal tissue regions.

The analysis includes:

* loading and processing PanNuke Fold 1 data
* running Cellpose segmentation masks
* comparing predicted masks with ground-truth annotations
* extracting morphology and intensity-based cell features
* comparing neoplastic and normal cell populations
* generating plots and summary statistics for interpretation

## Repository Structure

```text
quantitative_microscopy_final_project/
├── Fold_1/
│   └── cellpose_fold1_analysis/
├── pannuke_fold1_cellpose_neoplastic_vs_normal.ipynb
└── README.md
```

## Main Notebook

The main analysis is in:

```text
pannuke_fold1_cellpose_neoplastic_vs_normal.ipynb
```

This notebook performs the full workflow, including data loading, segmentation evaluation, feature extraction, visualization, and comparison of neoplastic versus normal cells.

## Requirements

The project was developed in Python using Jupyter Notebook. Main Python packages used include:

```text
numpy
pandas
matplotlib
seaborn
scikit-image
scipy
cellpose
```

## Output

The notebook produces summary tables and visualizations describing:

* segmentation performance
* object-level matching between prediction and ground truth
* cell size and shape distributions
* differences between neoplastic and normal cells
* example segmentation overlays
