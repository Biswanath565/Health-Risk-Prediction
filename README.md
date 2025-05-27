# Health-Risk-Prediction
ML-based health risk prediction using lifestyle data
## Project Overview
This project uses machine learning to predict health risk levels based on a variety of lifestyle and physiological data, such as sleep time, BMI, alcohol intake, physical activity, and more. It is based on a dataset available from Kaggle.
## Problem Statement
The goal is to build a machine learning model that can predict an individual's health risk level using easily available lifestyle indicators. This helps in early intervention and preventive care.
## Dataset
The dataset was sourced from [Kaggle](https://www.kaggle.com/) and contains anonymized health and lifestyle data.
**Features include:**
- Sleep Time
- Physical Activity
- BMI
- Alcohol Intake
- Smoking Status
- Age, Gender, Race
## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
## Model Building
The dataset was preprocessed to handle missing values and outliers. The data was then split into training and testing sets.
Several machine learning models were explored:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
The best-performing model was selected based on accuracy and F1 score.
---
pip install jupyterlab
### **Step 6: Add Results and Visualizations**
```markdown
## Results
The model achieved the following metrics on the test set:
- **Accuracy:** 85%
- **Precision:** 83%
- **Recall:** 82%
- **F1 Score:** 82%
Visualizations such as confusion matrix, ROC curve, and feature importance plots are included in the notebook.
## How to Run
Clone the repository:
```bash
git clone https://github.com/your-username/Health-Risk-Prediction.git
cd Health-Risk-Prediction
pip install -r requirements.txt
jupyter notebook ml-based-health-risk-from-lifestyle-data.ipynb
