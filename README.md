# data1030-project
This is my data 1030 project. I am predicting whether a patient would have died in a hospital or not based on the [SUPPORT2](https://archive.ics.uci.edu/dataset/880/support2) dataset. As this is a binary classification problem, the ML models trained in this project are logistic regression, decision tree classifier, random forest classifier, support vector classifier, and XGBoost classifier. 

The models_cv notebook has models that were trained using a stratified shuffle split, while the file models_no_cv has models trained using only a normal train test split. 

# Dependencies
- python=3.11.4
- matplotlib=3.7.2
- seaborn=0.12.2
- pandas=2.0.3
- scikit-learn=1.3.0
- numpy=1.24.4
- py-xgboost=1.7.6
- shap=0.42.1
- jupyter
