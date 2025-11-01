# Spatio-Temporal Health Analytics and Visualization


## Overview

Chronic diseases such as diabetes, cardiovascular disorders, and respiratory illnesses are among the leading causes of death worldwide.  
This project — **Spatio-Temporal Health Analytics and Visualization** — aims to leverage **Big Data technologies**, **Machine Learning**, and **Geospatial Analysis** to identify, predict, and visualize chronic disease patterns across the United States.

By combining large-scale health data processing with advanced visualizations and **Large Language Model (LLM)** integration, our system provides real-time insights to assist healthcare professionals, researchers, and policymakers in making informed decisions for better disease management.

---

## Objectives

- Automate data preprocessing for large-scale health datasets.  
- Analyze **spatio-temporal patterns** of chronic diseases using geospatial and temporal dimensions.  
- Employ **Machine Learning models** to predict disease prevalence.  
- Visualize patterns using intuitive maps, heatmaps, and charts.  
- Integrate **LLMs** to summarize data trends and suggest data-cleaning strategies dynamically.

---

## Key Features

### Big Data Processing with Apache Spark
- Handles over **1.19 million records** from the CDC Chronic Disease Indicators dataset.  
- Performs scalable distributed computation for real-time disease monitoring.  
- Uses Spark SQL for efficient querying, filtering, and aggregation.

### Machine Learning for Prediction
- Implements **Random Forest** and **Logistic Regression** models.  
- Evaluates model performance using:
  - Mean Absolute Error (MAE): `589.48`  
  - Mean Squared Error (MSE): `1,717,429.35`  
  - R² Score: `0.92`

### Geospatial Visualization
- Utilizes **GeoPandas** and **Matplotlib** for interactive data mapping.  
- Creates:
  - U.S. heatmaps showing regional disease prevalence  
  - Time-series plots for top 5 diseases  
  - Correlation heatmaps between diseases  
  - Bar and pie charts for state-level and national insights

### LLM Integration for Data Quality
- Uses an LLM (via prompting) to:
  - Assess data completeness  
  - Recommend preprocessing steps (dropna, fillna, etc.)  
  - Generate descriptive summaries of dataset health and trends  

---

## Dataset

**Source:** [CDC Chronic Disease Indicators (CDI)](https://catalog.data.gov/dataset/u-s-chronic-disease-indicators-cdi)  
**Records:** ~1.19 million  
**Attributes:** 34  
Includes data on:
- Disease prevalence
- Demographics
- Risk factors
- Geographic and temporal dimensions


