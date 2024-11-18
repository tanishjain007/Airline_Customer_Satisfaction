# Airline_Customer_Satisfaction
Table of Contents
Project Overview
Objective
Methodology
Technologies Used
Model Development
Results
Challenges Faced
Future Improvements
Conclusion
Project Overview
This project aims to predict airline passenger satisfaction using a Support Vector Machine (SVM) model. The goal is to classify passengers as satisfied or dissatisfied based on various features related to their flight experience.

Objective
The primary objective of this project is to build an SVM model that accurately predicts passenger satisfaction levels using historical data. The model helps airlines identify key factors that contribute to passenger satisfaction.

Methodology
Data Collection: Collected passenger data from [mention source].
Exploratory Data Analysis (EDA): Conducted EDA to understand the distribution of data and relationships between features and satisfaction levels.
Feature Selection: Identified the most relevant features for the model using correlation analysis and feature importance scores.
Model Building: Implemented an SVM classifier to distinguish between satisfied and dissatisfied passengers.
Model Evaluation: Evaluated model performance using metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Model Development
Support Vector Machine (SVM): Chose SVM due to its effectiveness in high-dimensional spaces and ability to handle non-linear decision boundaries with the kernel trick.
Hyperparameter Tuning: Used Grid Search with Cross-Validation to optimize hyperparameters such as C (regularization parameter), kernel type (linear, RBF), and gamma.
Results
Model Performance:
Accuracy: [61.95%]
Insights: Identified key drivers of passenger satisfaction, such as in-flight services and seat comfort.
Challenges Faced
Imbalanced classes with more dissatisfied passengers.
Feature scaling required careful handling due to different scales of input features.
Selecting the appropriate kernel and tuning hyperparameters for optimal performance.
Future Improvements
Integrate additional features like passenger demographics and flight duration.
Experiment with other classification algorithms such as Random Forest or Neural Networks for comparison.
Deploy the model as a web application or API for real-time satisfaction prediction.
Conclusion
The SVM model successfully predicts airline passenger satisfaction with reasonable accuracy, highlighting important factors influencing customer experience. Further refinements and integration with real-time data could enhance its practical application for airlines.

