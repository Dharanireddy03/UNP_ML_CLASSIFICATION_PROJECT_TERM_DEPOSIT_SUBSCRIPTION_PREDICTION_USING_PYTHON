# UNP_ML_CLASSIFICATION_PROJECT_TERM_DEPOSIT_SUBSCRIPTION_PREDICTION_USING_PYTHON
I completed this group project in collaboration with UNP (United Network of Professionals), applying Python-based machine learning to predict bank term deposit subscriptions through data preprocessing, exploratory data analysis, feature engineering, class-imbalance handling, classification, and model evaluation.

Project Overview
This project focuses on developing a machine learning-based approach to predict whether a bank customer is likely to subscribe to a term deposit. Using the Bank Marketing dataset, we analysed demographic, financial, and campaign-related attributes to identify patterns influencing customer subscription behaviour.
The project involves data preprocessing, feature engineering, exploratory data analysis, and the implementation of multiple classification algorithms. We also explored an Artificial Neural Network (ANN) to examine different modelling approaches and evaluate their predictive performance.

Project Objectives
Analyse customer and campaign-related data to understand subscription behaviour.
Prepare the dataset through data cleaning and feature engineering.
Identify meaningful patterns using exploratory data analysis.
Develop and compare multiple machine learning classification models.
Explore the application of an Artificial Neural Network.
Evaluate model performance using appropriate classification metrics.

Methodology
Data Understanding: Examined the dataset, its attributes, and the target variable.
Data Preprocessing: Cleaned the data, removed selected irrelevant attributes, and prepared it for analysis.
Feature Engineering: Created an income_group feature from the job attribute.
Exploratory Data Analysis: Used histograms, box plots, bar charts, pie charts, and correlation heatmaps to understand data distributions and relationships.
Data Transformation: Encoded categorical variables and prepared features for modelling.
Class Imbalance Handling: Applied SMOTE to the training data for traditional machine learning models.
Classification Modelling: Implemented five algorithms:
Logistic Regression
Decision Tree
Random Forest
Gradient Boosting
XGBoost
Artificial Neural Network: Experimented with different ANN architectures, optimisers, and batch sizes using TensorFlow and Keras.
Model Evaluation: Compared model performance using accuracy, precision, recall, F1-score, and confusion matrices.

Tools and Technologies :
Programming Language: Python
Data Manipulation: Pandas, NumPy
Data Visualisation: Matplotlib, Seaborn
Machine Learning: Scikit-learn, XGBoost
Class Imbalance Handling: Imbalanced-learn (SMOTE)
Deep Learning: TensorFlow, Keras
Environment: Google Colab / Jupyter Notebook

Key Results
Random Forest achieved the highest accuracy of 84.13% among the SMOTE-trained traditional classification models at the 60:40 train-test split.
Gradient Boosting achieved the highest recall of 41.69% and F1-score of 35.04% at the 80:20 split among those models.
The best-performing ANN configuration reported 89.46% accuracy and 16.62% recall.

Key Learnings
This project provided practical experience in data preprocessing, feature engineering, exploratory data analysis, handling imbalanced datasets, classification modelling, and model evaluation. It also demonstrated the importance of evaluating classification models using multiple performance metrics rather than accuracy alone.

GOOGLE COLAB LINK :
https://drive.google.com/file/d/1qbpB-QVC8jex77E65Y1FqHYfklcFQdXE/view?usp=drivesdk

PRESENTATION LINK : 
https://docs.google.com/presentation/d/1OQMHnlkYR_k0zazUOqoTy2XYv2W56a6N/edit?usp=drivesdk&ouid=104520695117016960736&rtpof=true&sd=true
