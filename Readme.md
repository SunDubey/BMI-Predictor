### Objectives

1.Create the training dataset based on the BMI business rules.<br />
2.Develop a model to predict BMI. The thinking process is more important than the actual model or model metrics.<br />
3.Write steps to operationalize the model.<br /><br />


# Install packages<br />
pip install -r requirements.txt<br />

# Content<br />
In BMI_Prediction.ipynb, there are 3 modules.<br />

**Create the training dataset based on the BMI business rules, directly calculate BMI with height and weight data.<br />**
**Predict BMI with BayesianRidge model. With standard Preprocessing and Feature Engineering such as standardization, Encoding.<br />** 
**Predict BMI with HuberRegressor  model. Alongwith standard preprocessing and feature engineering engineered Price_Quote feature which helps in increasing the correlation.<br />**

In BMI_Predictor.py, I have breaken up each step into different functions to operationalize the model.
