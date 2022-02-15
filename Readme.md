##Objectives

1.Create the training dataset based on the BMI business rules.<br />
2.Develop a model to predict BMI. The thinking process is more important than the actual model or model metrics.
3.Write steps to operationalize the model.


Install packages
pip install -r requirements.txt

Content
In BMI_Prediction.ipynb, there are 3 modules.

Create the training dataset based on the BMI business rules, directly calculate BMI with height and weight data.
Predict BMI with BayesianRidge model. With standard Preprocessing and Feature Engineering such as standardization, Encoding. 
Predict BMI with HuberRegressor  model. Alongwith standard preprocessing and feature engineering engineered Price_Quote feature which helps in increasing the correlation.

In BMI_Predictor.py, I have breaken up each step into different functions to operationalize the model.
