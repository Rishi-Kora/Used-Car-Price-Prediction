# Used Car Price Prediction

This project builds a machine learning model to predict the price of used cars based on features such as manufacturer, mileage, fuel type, and engine size. It is designed to help buyers and sellers make informed decisions in the used car market.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Methodology](#methodology)  
- [Results and Findings](#results-and-findings)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgments](#acknowledgments)

---

## Project Overview

The goal of this project is to predict the fair market value of used cars using machine learning techniques. The dataset is analyzed, cleaned, and modeled using a variety of regression algorithms to find the best fit.

---

## Dataset

The dataset includes the following features:

- Manufacturer  
- Model  
- Year of Manufacture  
- Mileage  
- Fuel Type  
- Transmission Type  
- Engine Size  
- Number of Owners  
- Location  
- Price (target variable)

Data preprocessing includes:

- Handling missing values  
- Encoding categorical variables  
- Removing outliers  
- Feature scaling

---

## Methodology

### 1. Data Collection & Preparation

- Data collected from public car listings.
- Cleaning, type conversion, and formatting for consistency.

### 2. Exploratory Data Analysis (EDA)

- Univariate and bivariate visualizations  
- Outlier detection  
- Correlation analysis

### 3. Feature Engineering

- Encoding of categorical variables  
- Extraction of new features from existing ones

### 4. Model Training

Models tested:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  

### 5. Model Evaluation

Metrics used:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

### 6. Deployment (Optional)

This notebook can be extended into a web app using frameworks like Flask or Streamlit.

---

## Results and Findings

- Engine size and car age are strong predictors of price.  
- Cars with automatic transmission and diesel engines generally hold higher value.  
- The Random Forest Regressor achieved the best performance on test data.  
- Feature importance analysis revealed useful pricing insights.

---

## Usage

To run the project locally:

```bash
# Clone the repository
git clone https://github.com/Rishi-Kora/Used-Car-Price-Prediction.git
cd Used-Car-Price-Prediction

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Used_Car_Price_Prediction.ipynb
