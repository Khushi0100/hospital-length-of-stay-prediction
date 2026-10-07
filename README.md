# Hospital Length-of-Stay Prediction

Predicts hospital length of stay using Python and machine learning.

## Tools
Python, Jupyter, pandas, scikit-learn

## Method
Cleaned and preprocessed the healthcare dataset, performed feature engineering, and evaluated multiple regression and classification approaches to identify predictors of patient length of stay.

## Results
Using an 80/20 train-test split, XGBoost achieved the best regression performance on the test set (49,747 records), with a mean absolute error (MAE) of 1.636 days, root mean squared error (RMSE) of 3.328 days, and R² of 0.8224. For the short, medium, and long stay classification task, Random Forest achieved 77.66% accuracy and a weighted F1 score of 0.7822.

Limitation: The regression models included total charges and costs, which are finalized at discharge. These features may not be available when a hospital needs to estimate length of stay at admission.

## Run
Open Team9_Hospital_LOS_Prediction_v2.ipynb in Jupyter Notebook or JupyterLab. Install the required packages with pip install pandas numpy matplotlib seaborn scikit-learn xgboost.
