# Modeling-Python-Scores-Feature-Significance-Behavioral-Patterns-and-Predicted-Improvement
This repository contain a project that involves data cleaning, EDA and predictive modelling. This project mainly revolve around studying the feature significance, studying behavioural patterns among bottom 10% peforming students against the rest, and predictive aspects for Linear Regression. 
Dataset link:  https://www.kaggle.com/datasets/walekhwatlphilip/intro-to-data-cleaning-eda-and-machine-learning/data

There are 3 goals of this project.
1. Identify the key features and their impact on Python score predictions
2. Explore behavioural patterns among bottom 10% performing students.
3. Measure model-predicted improvement in Python scores by enhancing high-impact features for bottom 10% students.

Goal 1:
1. ANOVA to identify the feature significance towards Python score.
2. 3D scatter plot using x and y for two most prominent features for Python score.
3. Correlation heatmap to identify correlate features.
4. Applied feature importance on Linear Regression model to find out which features results in highest impact in increasing Python score.

Goal 2:
1. Defined 10% quantile as the lowest performing students group.
2. Studied the similarities in features among the bottom 10% performing students against the rest.
   (stripplot for categorical columns, scatterplot for numerical columns)

Goal 3:
1. Evaluated linear, tree-based and regularized models with KFold of 5 using R2 score mean as metric.
2. Checked variance inflation factor to identify features that are collinear with other correlated feature.
3. Tested feature interaction and grouped column to reduce multicollinearity
4. Compared predicted Python scores before and after high coefficient feature enhancement.
