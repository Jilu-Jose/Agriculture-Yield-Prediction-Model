# Crop Production Prediction Based on Agro-Environmental Data

## Project Overview

This project aims to build a regression model using machine learning techniques to forecast crop yield based on various agro-environmental parameters such as rainfall, temperature, area, item, and pesticide usage. The system also provides feature importance analysis and interactive visualizations using Power BI to assist farmers, agronomists, and policymakers in decision-making and yield improvement.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Project Architecture](#project-architecture)
- [Installation Guide](#installation-guide)
- [Usage Instructions](#usage-instructions)
- [Model Evaluation](#model-evaluation)
- [Power BI Dashboard](#power-bi-dashboard)
- [Folder Structure](#folder-structure)
- [Challenges Faced](#challenges-faced)
- [Learnings](#learnings)
- [License](#license)

## Dataset Description

The dataset includes historical crop production records along with corresponding environmental parameters. Key columns include:

- Area
- Item (Crop Type)
- Year
- Average Rainfall per Year (mm)
- Pesticides Used (Tonnes)
- Average Temperature (°C)
- Yield (Tonnes/Hectare) [Target Variable]

## Technologies Used

- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)
- Power BI (for dashboard and interactive visualizations)
- Jupyter Notebook / VS Code
- Joblib (for model serialization)

## Project Architecture

1. **Data Collection and Cleaning**
2. **Outlier Detection and Removal (IQR Method)**
3. **Feature Encoding (LabelEncoder)**
4. **Feature Selection and Splitting**
5. **Model Training (RandomForestRegressor)**
6. **Model Evaluation and Saving**
7. **Prediction on New Data**
8. **Power BI Dashboard Visualization**


