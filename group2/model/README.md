Regression models were worked on and XGBoost Regressor emerged as the best model with a RMSE of 1686335.03921 on the train set and a RMSE of 1741204.57557 on the test set. The models however went through distinct but similar feature engineering. RandomForest Regressor was also dominant in most of the models and gave good predictions. 

The table below displays the models and the corresponding evaluation score on Kaggle;


| Models                                         | RMSE evaluation Score on Kaggle |
|------------------------------------------------|---------------------------------|
| XGBoost Regressor                              | 1741204.57557                   |
| Random Forest Regressor                        | 1755671.50948                   |
| GBM blended with Random Forest                 | 1761881.04484                   |
| Random Forest Regressor with selected features | 1763740.28117                   |
