# TCD_MSc-Dissertation_Tanvi-Bagla_19300699

As a part of coursework related to the 'Thesis' in Trinity College Dublin, I worked on the topic 'Comparative Analysis of NGBoost and XGBoost'. Following is the Abstract of the same.

## Abstract

Data scientists are coming up with new ensemble methods of machine learning by doing a little tweak in the way ensemble trees are learned, and the parameters are trained. The concept of Gradient Boosting Machines is running since 2001. Gradient boosting comprises of an ensemble of weak models that are combined to output
one strong prediction model. NGBoost (Natural Gradient Boost)
is one of the recent boosting models that has the feature of giving probabilistic predictions.
It is built on the principle where a base learner works on parametric probability
distributions to be measured on a scoring rule.

This study aims to investigate and compare NGBoost with another gradient boosting
method known as XGBoost. Both the models are applied to regression datasets
taken from the UCI Machine Learning repository. The robustness of the models is analyzed
based on hyperparameter tuning, K-fold validation, prediction accuracy calculated
though RMSE and performance speed (CPU/GPU speed).

The models output the point predictions and probabilistic predictions when applied to the
datasets. Through the experimental results, it is observed that NGBoost almost matches
the performance with that of XGBoost, although XGBoost being on the better side.
The RMSE scores are as follows: Regression datasets (Boston Housing Data: [NGBoost:
2.40], [XGBoost: 2.37]), (Protein Structure Data: [NGBoost: 3.58], [XGBoost: 3.44]).
NGBoost also has the power of giving predictions of uncertainty (prediction intervals) in
case of regression which XGBoost still lacks to predict.
