# Heart Attack Analysis and Prediction

This project aims to analyze and predict heart attacks using machine learning techniques. We will utilize the Heart Attack Analysis & Prediction Dataset available on Kaggle. The dataset contains various features such as age, sex, blood pressure, cholesterol levels, and other medical parameters, along with a target variable indicating whether a patient experienced a heart attack or not.

## Dataset
- **Source**: [Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset?select=heart.csv)
- **Features**: Various medical parameters and demographics.
- **Target Variable**: Whether a patient experienced a heart attack (0 for no, 1 for yes).

## Project Steps
1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables.
   - Scaling numerical features.
   - Splitting the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Statistical summaries.
   - Distribution of features.
   - Correlation analysis.
   - Visualization of relationships between features and target variable.

3. **Model Training**:
   - Utilizing various classifiers, including SVM with linear kernel.
   - Hyperparameter tuning using techniques like GridSearchCV.

4. **Model Evaluation**:
   - Calculating performance metrics such as precision, recall, F1-score.
   - Constructing confusion matrices.
   - Plotting ROC curves and Precision-Recall curves.

5. **Interpretation**:
   - Extracting classification rules from Decision Trees.
   - Analyzing feature weights from SVM with linear kernel.

## File Structure
- **README.md**: This file, providing an overview of the project.
- **heart.csv**: Dataset file.
- **heart_attack_prediction.ipynb**: Jupyter notebook containing the code for data preprocessing, EDA, model training, evaluation, and interpretation.
