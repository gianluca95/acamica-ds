# Data Science projects :bar_chart:

This is the repository for my Data Science projects developed at Acámica. 

You can clone and inspect them by executing the following command:
```
git clone https://github.com/gianluca95/acamica-ds
```

### [Project 1](https://github.com/gianluca95/acamica-ds/blob/main/DS_Proyecto_01.ipynb/)
I developed a Machine Learning model to predict house prices in Buenos Aires, Argentina. I did a thorough Exploratory Data Analysis, outliers detection and then I trained some models to get the best approach.

Comparing the three optimized models (LinearRegression, DecisionTreeRegressor and KNeighborsRegressor) it's concluded that the best results are obtained by the last one. We got a RMSE of 141.814 (USD) which is perfectible.

### [Project 2](https://github.com/gianluca95/acamica-ds/blob/main/DS_Proyecto_02.ipynb/)
The main goal of this project was to improve the results of Project 1. I focused on feature engineering (outliers detection, missing values and imputation, encoding, scaling and dimensionality reduction). Then I trained several and more complex models like BaggingRegressor, RandomForest, AdaBoost, Polinomial Regression and Ridge. Some of them were optimized with RandomSearchCV.

Results improved considerable: a RMSE of 32.193 (-78% reduction compared to Project 1).

By last, two clustering techniques were added (KMeans and DBSCAN) to detect possible similarity on neighborhoods areas around Buenos Aires or by the property types. It's concluded that DBSCAN fits better and a little interesting and "peculiar" group of houses were detected. 

### [Project 3](https://github.com/gianluca95/acamica-ds/blob/main/DS_Proyecto_03_ST.ipynb/)
Proyect 3 was based on predicting the vehicular flow of a Buenos Aires station. I did a thorough Exploratory Data Analysis, outliers detection and then I trained some time-series based models. As a first approach, I developed a benchmark model, one-step and multi-step prediction and then I used Prophet (Facebook based library) to reach the goal.

Best results are obtained by the one-step prediction (RMSE of 4790.99).
