# Ensemble-Technique

Ensemble learning is a general meta approach to machine learning that seeks better predictive performance by combining the predictions from multiple models.

Why ensemble Technque are famous ?
One of the main reason why ensemble technique are highly used because they solve a on of the major problem of machine leanring which is bias-varaince trade off .
We know that they are inversely related so changing in one result in decrease or increase in other accordingly . So Ensemble technique reduces the variance if your model has high variance then you should try once ensemble technique .

The three main classes of ensemble learning methods are bagging, stacking, and boosting.

Bagging involves fitting many decision trees on different samples of the same dataset and averaging the predictions.
Ex - Random Forest
Stacking involves fitting many different models types on the same data and using another model to learn how to best combine the predictions.
Boosting involves adding ensemble members sequentially that correct the predictions made by prior models and outputs a weighted average of the predictions.
Ex - XGBoost , AdaBoost , GradientBoost etc.
