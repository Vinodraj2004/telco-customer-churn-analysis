# Telco Customer Churn Analysis and Prediction Using Data Analytics and AI

**Student:** Vinodraj Badigera  
**Internship:** IBM SkillsBuild Data Analytics with AI Academic Internship Program

## 1. Project Description

This project analyzes customer churn in a telecommunications dataset and uses machine learning to predict whether a customer is likely to leave the service.

The project covers:
- Data loading
- Data cleaning
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature preprocessing
- Logistic Regression
- Random Forest Classification
- Model evaluation
- Confusion matrix and ROC curve
- Feature importance
- Example churn prediction

## 2. Dataset

The project uses IBM's public Telco Customer Churn sample dataset.

Dataset URL:

https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

The IBM repository describes an end-to-end workflow for loading, visualizing, analyzing and modeling the same customer-churn dataset.

## 3. Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 4. Project Structure

```text
VinodrajBadigera_TelcoCustomerChurn.ipynb
requirements.txt
Vinodraj Badigera_TelcoCustomerChurnReport.docx
README.md
```

## 5. Setup

Install Python 3.10 or later if possible.

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Open `VinodrajBadigera_TelcoCustomerChurn.ipynb` and run the cells from top to bottom.

## 6. Dataset Loading

The notebook first checks whether `Telco-Customer-Churn.csv` exists in the same folder. If it is not found, it loads the CSV directly from the documented IBM public URL.

For an offline run, download the dataset from the URL above and place it next to the notebook.

## 7. Machine Learning

The notebook trains two classification models:

1. Logistic Regression
2. Random Forest Classifier

The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix
- ROC curve

## 8. Important Note About Results

Run the notebook before final submission. The notebook generates the actual metric values, charts and feature-importance results. Do not manually invent model-performance numbers.

The train/test split uses `random_state=42`, so the same environment and dataset should produce reproducible results subject to library/version differences.

## 9. Academic Use

This project is intended as an academic internship project demonstrating a complete data analytics and machine-learning workflow. The model is a decision-support demonstration and should not be treated as a guaranteed prediction of individual customer behavior.
