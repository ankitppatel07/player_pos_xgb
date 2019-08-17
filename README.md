# Finding Best-Suited Playing Position Based On Football Player's Skills using Extreme Gradient Boosting
Project description:
- Preprocessed data which contains player information and skills, conducted EDA to determine which attributes to keep and exclude attributes that do not have a significant effect on the model
- Tuned hyperparameters to improve model performance from 86% to 87.5% using RandomizedSearchCV (with estimator as XGBClassifier, 10 Stratified K-folds, custom parameter grid for XGBoost) as GridSearchCV was computationally expensive and time-consuming

# Tech Stack: Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
