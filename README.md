# ReneWind_Project: Project Overview
* Created a tool that to measure and predict degradation and future component capability (Recall 0.85 on test data) using ciphered datasets
* Optimized Decision Tree, Random Forest, Logistic Regression, AdaBoost, Gradient Boost, XGBoost, Bagging Classifiers using Under/Oversampling, GridSearch CV and Hyperparameter tuning to reach the best model
## Code and Resources used
**Python version:** 8.2.0

**Packages:** pandas, numpy, sklearn, imblearn, matplotlib, seaborn, xgboost, statsmodels
## Data Cleaning
2 datasets (test and train data) were given. The datasets were ciphered and quite clean but they had missing data. The missing data were treated using KNN Imputer
## EDA
I looked at the distributon and pairplots of the features of the train dataset, I observed that they were almost all normally distributed

![EDA_normal_dist_univariate_edited](https://github.com/Ariyo347/ReneWind_Project/assets/113588909/bc7cf75d-0bba-4438-a676-00adde7211f1)


The paiplot added more insight to the failure pattern

![Pairplot](https://github.com/Ariyo347/ReneWind_Project/assets/113588909/79f74314-da86-4149-be73-aa6f5f8eb1df)

## Model Building
