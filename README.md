# TESS Light Curve Preprocessing and Transit Analysis Pipeline

This project implements a reproducible pipeline for downloading, cleaning, preprocessing,
and analyzing photometric light curves from the NASA TESS mission.

The pipeline is designed to work with **any user-specified TESS target (TIC ID)** and prepares
light curves for transit detection, evaluation, and future machine learning applications.

---

## Project Motivation

Transit photometry is highly sensitive to instrumental noise, data gaps, and systematic effects.
Before applying automated or machine learning–based methods, light curves must be carefully
cleaned and standardized.

This project focuses on building a **robust preprocessing and analysis pipeline** rather than
directly training a machine learning model.

---

## Notebook Workflow

The project consists of the following Jupyter notebooks, which must be run sequentially:

1. **01_project_overview.ipynb**
   - Scientific background and project scope

2. **02_data_loading.ipynb**
   - Automatic download of TESS light curves using the Lightkurve API

3. **03_preprocessing.ipynb**
   - NaN removal
   - Outlier rejection
   - Light curve flattening and normalization

4. **04_feature_extraction.ipynb**
   - Period search
   - Phase folding
   - Transit-related feature extraction

5. **05_false_positive_analysis.ipynb**
   - Inspection of transit-like signals
   - Identification of potential false positives

6. **06_evaluation.ipynb**
   - Scientific interpretation of results
   - Limitations and performance discussion

---

## Repository Structure


