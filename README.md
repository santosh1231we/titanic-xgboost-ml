# titanic-xgboost-ml
# 🚢 Titanic - Machine Learning from Disaster

This is my solution to the famous [Titanic Kaggle Competition](https://www.kaggle.com/competitions/titanic).

Achieved **~0.76 accuracy** on the public leaderboard using `XGBoost` with advanced features and `GridSearchCV`.

## 🧠 What I Did

- Cleaned missing values (Age, Fare, Embarked)
- Engineered features like:
  - `Title` from Name
  - `FamilySize` and `IsAlone`
  - `AgeBin` and `FareBin`
  - `Deck` from Cabin
  - `Pclass * Sex` interaction
- Tuned hyperparameters with `GridSearchCV`
- Used `XGBoostClassifier` as the final model

## 📂 Files

- `titanic_model.ipynb`: My full working Colab notebook
- `titanic_final_submission.csv`: The submission file I uploaded to Kaggle
- `README.md`: This file

## 🚀 Score

- Public Leaderboard Score: **0.76076**
- Cross-validation Score (5-fold): ~0.83

## ✍️ Author

Santosh  
_11th Grade Student | ML + Aerospace Enthusiast_  
_This is part of my AI portfolio for Jane Street + SpaceX future goals._
