# exoplanet

This aims to predict the presence of exoplanets from star data using various machine learning algorithms.

Data Preprocessing: It begins by loading star data, handling missing values with the SimpleImputer, and scaling features for better model performance.

Data Balancing: The dataset is balanced using SMOTE to create synthetic samples of stars with exoplanets, addressing class imbalance.

Model Training and Validation: The data is split into training and testing sets. A Decision Tree model is trained, and its accuracy is assessed on the validation set with a classification report.

ROC Curve Analysis: The ROC curve is generated to evaluate the model's performance, quantifying its ability to distinguish between classes.

Multiple Models: The training process is repeated for K-Nearest Neighbors (KNN) and Logistic Regression models, comparing their performances through accuracy and classification reports.

Final Predictions: Predictions are generated for the test data, displaying validation accuracies and performance metrics for each model.

Visualizations: Confusion matrices and ROC curves are created to visualize model performance and identify areas for improvement.

Conclusion: The output includes accuracy scores and detailed reports that provide insights into the effectiveness of each model in predicting exoplanets in star data.

