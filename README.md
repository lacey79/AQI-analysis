# Predicting Air Quality Based on Weather Factors

This repository is STAT451 project (Group 18) that aimed at predicting and classifying the Air Quality Index (AQI) using global weather data. The project explores the impact of meteorological and pollutant factors on AQI and analyzes climate patterns influencing air quality.

# Reference Links

- [World Weather Repository Dataset (Kaggle)](https://doi.org/10.34740/KAGGLE/DSV/10147597)
- [Technical Assistance Document for AQI Reporting](https://document.airnow.gov/technical-assistance-document-for-the-reporting-of-daily-air-quailty.pdf)
- [National Weather Service: Why Air Quality Is Important](https://www.weather.gov/safety/airquality)

# Getting Started

The project utilizes the Kaggle Global Weather Repository dataset, which includes over 37,000 observations and 41 features categorized into meteorological, pollutant, and geographic variables. The workflow involves:

1. **Data Preprocessing**:
   - Standardizing features
   - Handling missing values
   - Splitting data into training, validation, and test sets

2. **Modeling**:
   - Regression models: Linear regression, decision trees, gradient boosting, and random forests
   - Classification models: Logistic regression, k-NN, SVM, and random forests
   - Clustering analysis using K-means and PCA for climate-based grouping

3. **Evaluation**:
   - Models were evaluated based on Mean Squared Error (MSE), R², accuracy, and confusion matrices.

# What's Contained in This Project

This repository includes:

- **Data Analysis Scripts**: Python scripts for feature analysis, model training, and evaluation.
- **Visualization**: Plots for feature importance, clustering, and model performance.
- **Report**: Comprehensive findings and insights from the study.

## Key Findings

- Concentrations of pollutants such as Carbon Monoxide (CO), Sulfur Dioxide (SO₂), and Nitrogen Dioxide (NO₂) are the primary drivers of AQI variations.
- Random Forest provided the best results in both regression and classification tasks.
- K-means clustering revealed that regions with similar climates tend to share air quality profiles.

## Shortcomings and Improvements

- Address class imbalance in AQI categories.
- Incorporate temporal data for seasonal variations.
- Explore additional data sources for better predictions.



