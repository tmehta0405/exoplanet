# Exoplanet

This code is designed to predict the likely presence of exoplanets from star data with a variety of machine learning/deep learning algorithms.

Data Preprocessing: It starts with loading star data, handle it with missing value provider SimpleImputer and scale features for better model performance.

Data Balancing: Balanced the data using SMOTE to generate synthetic samples of the class of stars with exoplanets (addressing the class imbalance).

Model Training and Validation: The data is split into training and testing sets. A Decision Tree model is trained, and its accuracy is assessed on the validation set with a classification report.

ROC Curve Analysis: ROC curves are plotted to analyse model outputs in terms of abilities of class separation.

Multiple Models: This training routine is repeated for the K-Nearest Neighbors (KNN) and Logistic Regression models, then the performances are compared by evaluating accuracy and classification reports. 

Predictions: Here is where it all comes together in the test data, alongside validation accuracies and performance statistics for each model.

Visualisations: To visualise model performance and identify areas for improvement, confusion matrices and ROC curves can be produced.

Conclusion: The tests return scores of accuracy details and analysis of how well each model predicts exoplanets in the data of each star.
