# Classifying Shooting Incident Fatality

## Project Overview

This project aims to predict whether a shooting incident will result in a fatality using historical NYPD shooting incident data. Machine Learning classification models were developed to identify patterns associated with fatal and non-fatal incidents.

---

## Business Problem

Law enforcement agencies need data-driven insights to identify high-risk incidents and allocate resources effectively. Predicting fatal shooting incidents can help:

- Improve public safety planning
- Support resource allocation
- Identify high-risk locations
- Enable proactive crime prevention strategies

---

## Dataset

Dataset: NYPD Shooting Incident Data (Historic)

Target Variable:

- STATISTICAL_MURDER_FLAG

The dataset contains information related to:

- Incident location
- Date and time
- Borough
- Victim demographics
- Perpetrator demographics
- Incident characteristics

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Data Cleaning

- Removed irrelevant columns
- Handled missing values
- Encoded categorical variables
- Checked for duplicate records
- Prepared dataset for machine learning

---

## Feature Engineering

Created additional features including:

- Year
- Month
- Day
- Hour
- Weekend Flag

These features helped capture temporal patterns associated with fatal incidents.

---

## Exploratory Data Analysis (EDA)

Performed analysis on:

- Fatal vs Non-Fatal incidents
- Borough-wise shooting distribution
- Incident trends over time
- Correlation between features
- Demographic analysis

---

## Machine Learning Models

The following classification models were implemented:

### Logistic Regression

Used as a baseline classification model.

### Decision Tree Classifier

Used to identify decision rules and feature interactions.

### Random Forest Classifier

Ensemble model providing improved predictive performance.

### K-Nearest Neighbors (KNN)

Distance-based classification model.

### Support Vector Machine (SVM)

Margin-based classification model.

### Gradient Boosting Classifier

Boosting technique for improved accuracy.

---

## Hyperparameter Tuning

GridSearchCV was used to optimize Random Forest parameters and improve model performance.

---

## Model Evaluation

Evaluation Metrics:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Best Model

Random Forest Classifier achieved the best overall performance and was selected as the final model.

---

## Feature Importance

Important factors influencing fatal incidents included:

- Incident Location
- Incident Time
- Victim Demographics
- Perpetrator Demographics

---

## Visualizations

### Fatal vs Non-Fatal Distribution

![Target Distribution](images/target_distribution.png)

### Borough Analysis

![Borough Analysis](images/borough_analysis.png)

### Correlation Heatmap

![Heatmap](images/correlation_heatmap.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

---

## Business Impact

This project demonstrates how machine learning can support:

- Crime risk assessment
- Public safety planning
- Resource optimization
- High-risk area identification

---

## Future Improvements

- XGBoost Implementation
- LightGBM Implementation
- Real-Time Prediction Dashboard
- Streamlit Deployment
- Geographic Crime Risk Mapping

---

## Project Structure

```text
classifying-shooting-incident-fatality/
│
├── data/
│   └── NYPD_Shooting_Incident_Data.xlsx
│
├── notebook/
│   └── Classifying Shooting Incident Fatality.ipynb
│
├── presentation/
│   └── PPT.pptx
│
├── images/
│   ├── target_distribution.png
│   ├── borough_analysis.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Author

### Suyash Patil

LinkedIn: https://linkedin.com/in/yourprofile
