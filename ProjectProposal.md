# Project proposal for<br>*GETTING STARTED WITH KAGGLE COMPETITIONS*
Author: *MELISSA LIAO*

## 1. Why: Question/Topic being investigated 1pt
I would like to join and build up my machine learning skills through Kaggle competitions as it will improve my resume and learn from peers within the community.

## 2. How: Plan of attack 1pt
For Kaggle starters, the site recommends to get started with the Titanic Machine Learning problem to get used to how Kaggle competition works. I will create an account in Kaggle and follow through the steps for the Titanic problem suggested in https://www.kaggle.com/alexisbcook/titanic-tutorial. I will extend the problem by testing different models other than the one suggested in the tutorial and incorporate some of the template from previous lab assignments. 

Furthermore, if time allows to participate in another Kaggle competition, I would like to join in and try the Jigsaw Rate Severity of Toxic Comments problem https://www.kaggle.com/c/jigsaw-toxic-severity-rating/overview. It is a much bigger competition to follow through but I think the intent and importance of this real-world problem could contribute and help face the challenges we experience online.

## 3. What: Dataset, models, framework, components 2pts
- Kaggle competition url: *https://www.kaggle.com/c/titanic/overview/description*.

- Scikit-learn classifiers: LogisticRegression, RandomForestClassifier, GradientBoostingClassifier, SVC, BernoulliNB, GaussianNB, DecisionTreeClassifier.
    - If needed, apply preprocessing and scaling: LabelEncoder, OneHotEncoder, StandardScaler, MinMaxScaler, etc.
    - Testing and tuning hyperparameters: cross-validation and grid search.
    - Also use metrics: binary classification and ROC-AUC.


- The XGBoost classifier model could potentially be applied and explored if training and validation scores isn't satisfied from above models. I will try to follow through these guides to download and import the library in the notebook:
    - https://xgboost.readthedocs.io/en/latest/python/python_api.html
    - https://towardsdatascience.com/getting-started-with-xgboost-in-scikit-learn-f69f5f470a97 