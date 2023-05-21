# Analyzing-Lower-Torso-CurvesProject

Project type: Data analysis project

Group Members: Zongjie Yin, Wenxuan Hong, Aristotle Kolefas, Diane Xu, Fanjun Zeng.

Presentation Link: [https://youtu.be/ZL3HLnLIlNs](https://www.youtube.com/watch?v=bRpAkSgQHzY)

Situation: The lower torso curve is integral to determining how pants fit on the body. The crotch curve in pants patterns is often drawn carelessly, leading to fit issues.

Actions:
1. Preprocessed some of the body measurement dataset such as remove not informative data to ensure data integrity and consistency;
2. Created informative variables for modeling;
3. Performed cluster maps and correlation matrixes on data visualization part;
4. Used SMOTE to solve the data imbalance problem and predicted the race of each individual for machine learning by Logistic Regression, Random Forest, XGBoost;
5. Evaluated model performance using appropriate evaluation metrics and validated on a holdout dataset;
7. Provided actionable insights and recommendatations.

Result: Unfortunately, the clustering approach did not provide evidence that the features are strong predictors of race. However, we achieved an accuracy of 0.86 in predicting the race of each individual, and the feature importance graphs implied the great significance of the coefficients of front and back curves.
