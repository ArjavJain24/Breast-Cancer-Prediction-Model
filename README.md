# Breast-Cancer-Prediction-Model
This project aims to build a machine learning model that can accurately predict whether a breast tumor is benign or malignant, using the Breast Cancer Wisconsin dataset. Early detection of breast cancer is critical, and this model supports that goal by automating diagnosis through data analysis.

The dataset contains various medical measurements (like radius, texture, smoothness, etc.) computed from digitized images of fine needle aspirates (FNA) of breast masses. These features are used to train classification algorithms.

The steps followed in the project include:

Data Exploration and Preprocessing:
The dataset is first loaded and explored to check for missing values and understand feature distributions. Correlation analysis is performed to identify important features. The features are then normalized using StandardScaler to ensure all inputs are on the same scale.

Model Building and Training:
The dataset is split into training and testing sets. Multiple machine learning models are trained and compared:

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree Classifier

Random Forest Classifier

Model Evaluation:
Each model is evaluated using metrics like accuracy, confusion matrix, and classification report (precision, recall, F1-score). These help determine which model performs best in classifying the tumors correctly.

The models show high performance, with some achieving over 95% accuracy. Among them, Random Forest and SVM provide the most consistent and reliable results.
