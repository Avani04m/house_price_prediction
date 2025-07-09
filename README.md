# house_price_prediction
This project focuses on predicting house prices in Bengaluru using machine learning. It involves cleaning the data, performing data analysis and building a regression model to estimate housing prices based on various features such as location, size, number of bedrooms and more.
---
## What This Project Includes
- Data cleaning and preprocessing which inculdes
  - removing missing values
  - conerting size to number of bedrooms
  - converting total_sqft entries to numeric , so that ranges and special formats can be handled
  - removed outliers in bath, price_per_sqft and bhk features
- Feature engineering
  - Created a new feature - 'price_per_sqft'
  - One Hot Encoded the location feature
  - Standarduzed numerical columns
- Used several models including linear regression, lasso regression , decision tree regressor to compare performance
---
## Libraries used
- Python
- Pandas,numpy
- Mathplotlib , Seaborn
- scikit-learn
---
## Dataset
- Source: [Kaggle house price dataset](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
- License: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
- **Note:** Only dataset is taken from Kaggle . All code and analysis is done by me in this project.
---
## Files
- housing.ipynb - Main Jupyter Notebook
- housing.csv - Dataset for analysis

