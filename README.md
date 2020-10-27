# Stacked Generalization Ensemble Learning for Air Pollutant Concentration Prediction
We aim to create an regressor ensemble model composed of models which are analyzed separately and then combined together using the stacked generalization algorithm from the sklearn library.

There are five primary regressor models that compose the ensemble:
1. Direct SVR (Support Vector Regression)
2. Random Forest
3. Stochastic Gradient Boosting
4. K-Nearest Neighbors
5. Recurrent SVR

all of these models and the stacking ensemble can be found in the [python sklearn library](https://scikit-learn.org/stable/index.html)
