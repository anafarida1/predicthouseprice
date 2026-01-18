House Price Prediction with Machine Learning

In this project, I predicted house prices using a dataset of 2,919 rows, split into 1,460 training and 1,459 testing samples, 
based on 8 key features such as LotArea, YearBuilt, OverallQual, OverallCond, GrLivArea, GarageArea, KitchenQual, and MiscFeature.

Categorical features were handled using Label Encoding for KitchenQual and One-Hot Encoding for MiscFeature. 

I trained Linear Regression, Lasso Regression, and XGBoost models using 5-Fold Cross Validation.
The results show Linear and Lasso Regression achieved R² = 0.772, while XGBoost performed best with a mean R² of 0.8063. 

Although XGBoost reached a training R² of 0.9968, an RMSE of 4,486 indicates that predicted house prices differ from actual prices by about ±4,486 USD on average.
Overall, XGBoost captured complex patterns better, while linear models provided strong and interpretable baselines.
