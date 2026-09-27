# Fresnel-Diffraction-Phase-Domain-walls
This repository contains the 2D array datasets and custom code package required to visualize experimental domain images and Fresnel diffraction simulation patterns. 
## 📂 Repository Structure

```text
├── README.md                  # This documentation file
├── Analysis_simulations_script.ipynb       # IPython Notebook for image analysis and Fresnel diffraction simulation pipeline
└── source_data/               # Raw 2D array data (CSV)
    ├── Fig3_FigS5_PanelA_array.csv
    ├── Fig3_FigS5_PanelB_array.csv
    ├── Fig3_FigS5_PanelC_array.csv

---

## Software Requirements

### Operating System
* Tested on: Scientific Linux 7 (SL7) / Windows 11 

### Software Stack & Versions
This pipeline was developed using **Python v3.12.14** and relies on the following core scientific libraries:
* `numpy` (v2.5.2)
* `scipy` (v1.18.0)
* `matplotlib` (v3.10.9)

No specialized or non-standard hardware is required. A standard desktop or laptop computer is sufficient to run all scripts.

## Installation & Environment Setup

We recommend using the web-based, interactive computing notebook environment **Jupyter**. 

You do not need to install any packages manually via the terminal. The required libraries will install automatically when you execute the very first cell inside the notebook. Expected installation time is **less than 3 minutes**.

1. Download the 'source_data_scripts' folder and place it directly inside the directory where your notebook is saved.
2. Launch Jupyter Notebook and open 'Analysis_simulations_script.ipynb'.
3. Execute the first cell to install `numpy`, `scipy`, `matplotlib`, `matplotlib-scalebar`, `ipywidgets`, and `ipympl`.

## Demo & Execution Guide

### Interactive Image Analysis and Fresnel Diffraction Simulation (`Analysis_simulations_script.ipynb`)
Execute all cells or some specific cells to reproduce the  desired Figures.
```
* **Expected Output:** The notebook will load the 2D arrays from the `source_data_scripts/` folder, execute the background processing steps, and regenerate the exact visual plots and colormaps featured in **Fig. 3**, **Fig. S3**, **Fig. S5**, and **Fig. S6**.
* **Run Time:** Expected execution time for the entire notebook is **~4 minutes** on a standard desktop.
