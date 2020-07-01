The data consists of different variables that may impact the credit score of different applicants.
The machine learning model is built up by 2 scenarios (duration <= 12 months or > 12 months)
The preliminary analysis is first conducted to examine outlier and overall data distribution via boxplot. Heatmap is also used to roughly examine the correlation between each variable and the credit score result.
The scorecardpy package especially woe (weight of evidence) is used to find out the impact level of different variables to result.
Different model training algorithms such as linear regression and logistic regression are used.
The performance is evaluated by KS (Kolmogorov–Smirnov) and AUC (Area under the ROC Curve) values.
