# kaggle-titanic
My solution for the classic Titanic competition at Kaggle, inspired by previous community efforts. When I run it on Kaggle I got an accuracy of 78.708 % on the test data, and 84.063% on the training data, which could indicate that the model overfits. Maybe stronger regularization, cross-validation, better feature selection or feature engineering could improve the accuracy?

Prediction made with a multi-model approach, combining the predictions of a Random Forest, XGBoost, K-Nearest Neighbors, Logistic Regression and Support Vector Machine model, all trained using scikit-learn. Challenge includes the handling of missing values and solution includes some feature engineering (creating new variables for family size), see the Jupyter notebook for the code. 

## Links
 https://www.kaggle.com/c/titanic
