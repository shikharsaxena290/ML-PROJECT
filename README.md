Algerian Forest Fire Prediction using Lasso Regression
This project aims to predict the Fire Weather Index (FWI) using various meteorological and forest-related parameters. The prediction model is built using the Algerian Forest Fire dataset and employs Lasso Regression for modeling. The project includes data cleaning, exploratory data analysis (EDA), model training, and deployment through a Flask web application.

Table of Contents
Overview
Dataset
Project Structure
Installation
Usage
Results
Contributing
License
Acknowledgements
Overview
The objective of this project is to predict the Fire Weather Index (FWI) using the following features:

Temperature
Relative Humidity (RH)
Wind Speed (Ws)
Rain
Fine Fuel Moisture Code (FFMC)
Duff Moisture Code (DMC)
Initial Spread Index (ISI)
Classes
Region
The model achieves an accuracy of 98% and is deployed as a web application using Flask.

Dataset
The dataset used in this project is the Algerian Forest Fire dataset, which contains various meteorological and forest-related parameters. The dataset is split into different regions and contains the following features:

Temperature
Relative Humidity (RH)
Wind Speed (Ws)
Rain
Fine Fuel Moisture Code (FFMC)
Duff Moisture Code (DMC)
Initial Spread Index (ISI)
Classes
Region
Fire Weather Index (FWI) [Target]

Algerian_Forest_Fire_Prediction/
│
├── notebook/
│   ├── data_cleaning_and_eda.ipynb
│   ├── model_training.ipynb
│
├── models/
│   ├── lasso_model.pkl
│   └── scaler.pkl
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── app.py
├── requirements.txt
├── README.md
└── dataset/
    └── Algerian_forest_fires_dataset.csv
Results
The Lasso Regression model achieves an accuracy of 98% on the test dataset. The model is able to predict the Fire Weather Index (FWI) based on the input features with high accuracy.
