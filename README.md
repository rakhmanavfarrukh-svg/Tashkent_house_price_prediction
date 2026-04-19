# Tashkent House Price Prediction

A machine learning project that predicts house prices in Tashkent based on property features such as size, location, number of rooms, and floor level.

---

## Problem Statement
Real estate prices vary significantly based on multiple factors. The goal of this project is to build a regression model that can estimate house prices in Tashkent with good accuracy.

---

## Learning Dataset
The dataset includes real estate listings with the following features:

- District (location)
- Size (m²)
- Number of rooms
- Floor level
- Total floors
- Price (target variable)

---

## Data Preprocessing
- Handled missing values
- Converted object types to numerical values
- Removed invalid / noisy entries
- Applied feature scaling
- Outlier treatment for better model stability


## Machine Learning Models
The following models were tested:

- Linear Regression
- Random Forest Regressor
- Support Vector Machine (SVM)

---

## Best Model Performance
- **Model:** Random Forest / SVM (best tuned)
- **Accuracy (R² Score):** ~0.81
- Good balance between bias and variance

---

## Feature Engineering
- Encoded categorical variables
- Created new features from existing columns
- Normalized numerical features using StandardScaler

---

# Author
## Farrukhbek Rakhmonov
Machine Learning Enthusiast | Data Science Learner

## Project Structure

---

## How to Run This Project

```bash
git clone https://github.com/rakhmanavfarrukh-svg/Tashkent_house_price_prediction.git
cd Tashkent_house_price_prediction
pip install -r requirements.txt
