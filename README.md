# Met-Office-Temp-Prediction

**_Task Description:_** Many primary sectors depend on the weather for production, such as farming and energy. The climate is changing at drastic rates making old weather prediction methods less effective. To overcome these difficulties, improved and reliable weather prediction methods are required. These predictions affect a nation's economy and the lives of people. Machine learning is being increasingly implemented into weather services and climate research, increasing accuracy and providing new pathways to mitigation and adaptation. This project aimed to predict mean temperatures in London, to assess the ability of a range of machine learning models to accurately predict weather elements based on previous research findings.

**_Method:_** The project utilised open-source Met Office data downloaded from kaggle (https://www.kaggle.com/datasets/muthuj7/weather-dataset) to predict recent mean temperatures in London. 

Data preprocessing for this project involved exploring the data and identifying and handling missing values. Feature engineering techniques were also used to calculate the mean temperature to use as the target variable.

Exploratory data analysis was conducted, using descriptive statistics and visualisations to identify distributions, patterns, outliers, and correlations.

A research review conducted by Bogdan and Zbigniew (2022) suggested that the most common machine learning models used in weather prediction and climate science research were Deep Learning, Random Forest, Artifical Neural Networks, Support Vector Machine and XGBoost, respectively. Random Forest Regressor, Support Vector Regressor and Artifical Neural Networks (ANN) were selected to predict mean temperature in London. Experimental hyperparameter tuning took place to optimise model performance and the evaluation strategy consisted of using cross validation (k=5) and evaluation metrics including MSE, MAE, RMSE and R2.

This project is currently still underway
