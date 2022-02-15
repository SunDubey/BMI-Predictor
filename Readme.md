Objectives
Create the training dataset based on the BMI business rules.
Develop a model to predict BMI. The thinking process is more important than the actual model or model metrics.
Write steps to operationalize the model.
Install packages
pip install -r requirements.txt
Content
In analysis.ipynb, there are 3 modules.

Directly calculate BMI with height and weight data
Predict BMI with random forest model. With standard feature engineering techniques (normalization, gender to dummy)
Predict BMI with random forest model. Besides adopting standard feature engineering techniques, handcraft 3 extra variables to reflect BMI business rules
In train.py, I break up each step into different functions to operationalize the model.