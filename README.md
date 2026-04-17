Tashkent House Price Prediction

Machine Learning project to predict house prices in Tashkent.
It predicts the houses lower than (<500m**2) and price should be lower than (<1,000,000$)

Dataset

Features:

* district, rooms, size, level, max_levels, price

Workflow

* Data cleaning (numeric conversion, missing values)
* Feature engineering (`size_per_room`)
* One-Hot Encoding for district
* Scaling + preprocessing pipeline

Models

* Linear Regression
* Random Forest

Results
* Linear Regression
* MAE ≈ 23,000
* Random Forest
* MAE ≈ 5,000
Tech

Python, Pandas, NumPy, Scikit-learn

👨‍💻 Author

Farrukhbek Rakhmonov
