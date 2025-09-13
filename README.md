# Predicting Heart Disease Using Machine Learning

This project uses Python and machine learning techniques to build a model that predicts whether a person has heart disease based on their medical attributes.

---

## Problem Definition

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

---

## Dataset

The dataset used is the Cleveland Heart Disease dataset from the UCI Machine Learning Repository:  
[UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)

An alternate source is also available on Kaggle:  
[Kaggle Heart Disease Classification Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset/data)

---

## Evaluation Metric

The goal is to achieve **95% accuracy** in predicting the presence or absence of heart disease.

---

## Features Description

| Feature  | Description                                                                                                 |
| -------- | ----------------------------------------------------------------------------------------------------------- |
| age      | Age in years                                                                                               |
| sex      | 1 = male; 0 = female                                                                                       |
| cp       | Chest pain type:                                                                                           |
|          | - 0: Typical angina                                                                                        |
|          | - 1: Atypical angina                                                                                       |
|          | - 2: Non-anginal pain                                                                                       |
|          | - 3: Asymptomatic                                                                                          |
| trestbps | Resting blood pressure (mm Hg)                                                                             |
| chol     | Serum cholesterol in mg/dl (above 200 is cause for concern)                                                 |
| fbs      | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)                                                      |
| restecg  | Resting electrocardiographic results:                                                                       |
|          | - 0: Normal                                                                                                 |
|          | - 1: ST-T wave abnormality                                                                                   |
|          | - 2: Possible left ventricular hypertrophy                                                                 |
| thalach  | Maximum heart rate achieved                                                                                 |
| exang    | Exercise induced angina (1 = yes; 0 = no)                                                                   |
| oldpeak  | ST depression induced by exercise relative to rest                                                         |
| slope    | The slope of the peak exercise ST segment:                                                                 |
|          | - 0: Upsloping                                                                                               |
|          | - 1: Flat                                                                                                    |
|          | - 2: Downsloping                                                                                             |
| ca       | Number of major vessels (0-3) colored by fluoroscopy                                                        |
| thal     | Thalium stress test results:                                                                                |
|          | - 1, 3: Normal                                                                                               |
|          | - 6: Fixed defect                                                                                            |
|          | - 7: Reversible defect                                                                                       |
| target   | Presence of heart disease (1 = yes; 0 = no) — this is the target variable                                    |

---

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Install required Python libraries (preferably in a virtual environment):
    ```bash
    pip install -r requirements.txt
    ```
3. Run the main notebook or script to train and evaluate the model:
    ```bash
    jupyter notebook heart_disease_prediction.ipynb
    ```
    or
    ```bash
    python main.py
    ```

---

## Project Structure

- `data/` — contains the dataset files  
- `model/` — saved machine learning model files  
- `notebooks/` — Jupyter notebooks with exploratory data analysis and modeling  
- `src/` — source code scripts  
- `README.md` — project overview and instructions  

---

## Results & Experimentation

Our model achieved an accuracy score of **98.76%** on the test dataset, which exceeds the project goal of 95%. This indicates the model is highly effective at predicting the presence of heart disease based on the clinical features.
