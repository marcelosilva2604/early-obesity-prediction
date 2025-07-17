# Early Obesity Prediction Project

A comprehensive data preprocessing and analysis pipeline for early obesity prediction using the ENANI 2019 dataset.

## Project Structure

### 1. Data Preprocessing Pipeline
- **A-Age Sample Filter**: Age filtering and sample selection
- **B-Missing Values Feature Removal**: Missing value analysis and feature removal
- **C-Near Zero Variance Removal**: Near zero variance feature elimination
- **D-Data Characteristics**: Data characteristics analysis

### 2. Feature Engineering
- **A-Correlation24MoxFeatures0-100**: Correlation analysis (features 0-100)
- **B-Correlation24MoxFeatures100-200**: Correlation analysis (features 100-200)
- **C-Correlation24MoxFeatures200-300**: Correlation analysis (features 200-300)
- **D-Correlation24MoxFeatures300-326**: Correlation analysis (features 300-326)
- **E-SUMReducedFeatures**: Final feature engineering and dataset optimization

## Data Files

Large CSV and TXT data files are excluded from the repository via `.gitignore` due to GitHub file size limits. The project structure and Jupyter notebooks are preserved for reference.

## Dataset

This project uses the ENANI 2019 dataset for nutritional analysis and early obesity prediction in Brazilian children.