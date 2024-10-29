# Retinal-Microglia-Segmentation


## Overview
This project provides a workflow for segmenting retinal microglia in Alzheimer's Disease (AD) datasets using a random forest classifier, trained with Ilastik. The code in this repository automates segmentation and quality control, enabling quantitative analysis of microglial morphology.

## Notebooks
- **Microglia_Ilastik_Segmentation.ipynb**: Notebook to perform segmentation using the Ilastik random forest classifier.
- **QC_Notebook.ipynb**: Notebook for quality control and validation of segmentation results.

## Installation
1. Clone the repository.
   ```bash
   git clone https://github.com/YourUsername/RetinalMicrogliaSegmentation.git
   
2. Install required dependencies.

   ```bash
   pip install -r requirements.txt


## Usage

    Follow instructions in Microglia_Ilastik_Segmentation.ipynb to segment retinal microglia.
    Run QC_Notebook.ipynb to check segmentation quality and validate results.

## Results

This pipeline generates segmented regions of interest for microglia in 3D, including metrics such as cell volume, perimeter, and morphology.
