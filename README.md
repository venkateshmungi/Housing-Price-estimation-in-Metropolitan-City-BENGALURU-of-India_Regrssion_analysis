# Housing-Price-estimation-in-Metropolitan-City-BENGALURU-of-India_Regrssion_analysis_using_Pycaret_and_Sklearn

Housing Price estimation in Metropolitan City [BENGALURU] of India_Regrssion_analysis_using_Pycaret_and_Sklearn

About Dataset

Context

The real estate markets in Bangalore / Bengaluru, present an interesting opportunity for data analysts to analyze and predict where property prices are moving towards. Prediction of property prices is becoming increasingly important and beneficial. Property prices are a good indicator of both the overall market condition and the economic health of a country. Considering the data provided, we are wrangling a large set of property sales records stored in an unknown format and with unknown data quality issues.

Content

Columns:

Area Type: Type of Plot

Availability: Ready to Move or Not

Location: Region of Bangalore

Size: BHK

Society: Colony in which the House is Present in

Total Sq. Ft: Total Area

Bath: Number of Bathrooms

Balcony: Number of Balconies

Price: Cost in Lakhs

Dataset Reference : https://www.kaggle.com/datasets/aryanfelix/bangalore-housing-prices?select=BHP.csv

CONCLUSION


* In this Project i've done feature engineering Techniques like StandardScaler, ColumnTransformer, SimpleImputer, OneHotEncoder in single pipe line using scikit-learn pipeline.

* Regression Algorithms has been applied, among all KNN Regressor was selected based on R2 score 0.99 and RMSE Score 7.07. These  are the best scores among all. 

* Ideally, lower RMSE and higher R-squared values are indicative of a good model. 

* The RMSE value 7.07 tells us that the average deviation between the predicted house price made by the model and the actual house price.

* The R2 value tells us that the predictor variables in the model (square footage, bathrooms, and bedrooms) are able to explain 99.7 % of the variation in the house prices.

* Based on above scores i used to download KNN model for real time prediction.

