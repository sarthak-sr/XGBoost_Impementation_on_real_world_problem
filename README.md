# XGBoost_Impementation_on_real_world_problem
- The Data SET is taken from Kaggle. Please refer: https://www.kaggle.com/code/chitwanmanchanda/engine-rating-predictions/input
- The problem statement is clearly mentioned in the Problem_Statement pdf file.
- An open ended EDA is done on the dataset
- Use of pipelines and transformers is well depicted in the notebook.
- XGBoost Regression model is implemented to predict the final value.
- Hyper-parameter tuning using GridserachCV is implemented. 
- In order to detect outliers, predictions from XGBoost model were made and any actual value which was off by 2.0 was categoried as outlier.
- These outliers were seperately saved in a CSV file. 
