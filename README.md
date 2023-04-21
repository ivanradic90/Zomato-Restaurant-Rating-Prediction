Zomato Restaurant Rating Prediction
This project uses machine learning algorithms to predict the rating of restaurants on Zomato based on various features such as location, cuisine, cost for two, etc.

Data
The data used in this project was obtained from Kaggle. It consists of 51,717 restaurant listings from Bangalore, India.

Data Preprocessing
The data was preprocessed by cleaning missing and duplicate values, handling outliers, encoding categorical variables, and scaling numerical features.

Modeling
Four machine learning models were trained on the preprocessed data: Linear Regression, KNN Regression, Decision Tree Regressor, and Random Forest Regressor. The performance of these models was evaluated using Mean Squared Error (MSE) and R-squared (R^2) score.

Results
The Random Forest Regressor performed the best with an MSE of 0.0965 and an R^2 score of 0.8995 on the test set. Further tuning of hyperparameters and feature selection could potentially improve the model's performance.

Project Files
zomato_data.csv: the raw data obtained from Kaggle
zomato_data_cleaned.csv: the cleaned data after preprocessing
modeling.ipynb: a Jupyter Notebook containing the data preprocessing and machine learning modeling process
random_forest_model.joblib: a trained Random Forest Regressor model saved using joblib
Usage
To use this project, download or clone the repository and run the modeling.ipynb notebook. Make sure the necessary libraries are installed.

Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
Credits
Data Source: Zomato Bangalore Restaurants
Author: Ivan Radic
