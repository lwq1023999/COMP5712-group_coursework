# Wine Market Characteristics and Pricing Analysis

## Overview
This repository contains the group coursework project for the COMP5712 Programming for Data Science module at the University of Leeds.

The project analyses wine market data to identify factors that influence wine pricing and market characteristics. Using Python and Jupyter Notebook, we perform data preprocessing, exploratory data analysis (EDA), visualisation, and machine learning to understand how different attributes affect wine prices.

Key attributes analysed include grape variety, region, alcohol content (ABV), vintage year, capacity, and wine type.

---

## Project Objectives

The main objectives of this project are:

1. Identify the key factors influencing wine pricing using exploratory data analysis (EDA).
2. Investigate regional wine price patterns across different countries.
3. Analyse price distribution across wine categories such as wine type and style.
4. Build a classification model to categorise wines into different price ranges.

---

## Dataset

The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/elvinrustam/wine-dataset/data) and contains wine information scraped from Majestic Wine, a UK wine retailer. The dataset contains approximately 1200 wine records with multiple attributes describing wine characteristics, origin, and pricing.

### 1. General Wine Identification
Basic information describing each wine product.

- **Title** – Name of the wine  
- **Description** – Textual description of wine features  
- **Vintage** – Year the grapes were harvested  
- **Type** – Wine category (e.g., red, white, sparkling, dessert)  
- **Style** – Sensory characteristics such as *rich & juicy* or *savoury & full-bodied*

### 2. Geographical Context
Information about the wine’s origin.

- **Country** – Country where the wine was produced  
- **Region** – Specific geographical region of production  
- **Appellation** – Legally defined wine-growing region

### 3. Technical Wine Characteristics
Attributes describing the wine’s composition.

- **Grape** – Primary grape variety  
- **Secondary Grape Varieties** – Additional grapes used in blends  
- **ABV (Alcohol by Volume)** – Alcohol percentage of the wine  
- **Unit** – Alcohol units determined by bottle size and ABV  
- **Closure** – Type of bottle closure (e.g., cork, screw cap)

### 4. Commercial Attributes
Market-related characteristics of the wine.

- **Price** – Cost of the wine (£)  
- **Per Bottle / Case / Each** – Sales format of the product  
- **Capacity** – Bottle volume or size  
- **Characteristics** – Flavor notes such as aromas and taste descriptors

---

## Project Workflow

The project follows a typical data science pipeline:

### 1. Data Collection
- Import dataset from Kaggle.

### 2. Data Preprocessing
- Handle missing values.
- Clean numerical attributes such as Price, Capacity, and ABV.
- Convert categorical variables.
- Perform feature engineering.

### 3. Exploratory Data Analysis (EDA)
- Analyse price distribution.
- Study relationships between price and attributes such as:
  - ABV
  - Capacity
  - Vintage year
  - Wine type

### 4. Data Visualisation
- Generate plots using:
  - Boxplots
  - Scatter plots
  - Distribution plots
  - Bar charts

### 5. Machine Learning
- Build classification models to predict wine price categories using:
  - Random Forest
  - K-Nearest Neighbours (KNN)

---

## Technologies Used

**Programming Language**

- Python

**Libraries**

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly

**Environment**

- Jupyter Notebook

---

## Repository Structure
