# AI-ML-Internship-Task-5
Train-Test Split &amp; Evaluation Metrics
# Heart Disease Prediction (Logistic Regression)

**Task 5: Train-Test Split & Evaluation Metrics** *AI & ML Internship*

## 📌 Project Overview
This project involves building a machine learning model to predict whether a patient has heart disease based on various medical attributes (such as age, cholesterol levels, and blood pressure).

The primary focus of this task was to understand the importance of **Train-Test Splitting** and to evaluate the model using standard classification metrics to ensure it generalizes well to unseen data.

## 📂 Dataset
* **Name:** Heart Disease Dataset
* **Description:** The dataset contains 1025 patient records with 14 attributes.
* **Target Variable:** `target` (1 = Disease, 0 = No Disease)
* **Key Features:** Age, Sex, CP (Chest Pain Type), Trestbps (Resting Blood Pressure), Chol (Cholesterol), etc.

## 🛠️ Technologies Used
* **Python**
* **Pandas** (Data Manipulation)
* **Scikit-learn** (Model Building & Evaluation)
* **Google Colab** (IDE)

## ⚙️ Methodology
1.  **Data Loading:** Loaded the `heart.csv` dataset.
2.  **Data Splitting:** Split the data into **Training (80%)** and **Testing (20%)** sets.
    * *Why?* To simulate real-world performance and prevent overfitting.
3.  **Model Training:** Trained a **Logistic Regression** model using the training set.
4.  **Prediction:** Generated predictions on the unseen test set.
5.  **Evaluation:** Calculated Accuracy, Precision, Recall, and the Confusion Matrix.

## 📊 Evaluation Results
The model was evaluated on 205 test samples. Here are the performance metrics:

* **Accuracy:** `79.51%`
    * *The overall percentage of correct predictions.*
* **Precision:** `75.63%`
    * *Accuracy of positive predictions (minimizing False Positives).*
* **Recall:** `87.38%`
    * *Ability to detect actual cases (minimizing False Negatives).*

### Confusion Matrix Breakdown
| | Predicted: Healthy | Predicted: Disease |
| :--- | :---: | :---: |
| **Actual: Healthy** | **73 (TN)** | 29 (FP) |
| **Actual: Disease** | 13 (FN) | **90 (TP)** |

*Observation: The model performs well with a high Recall (87%), which is crucial in medical diagnosis to minimize missed cases.*

## 🧠 Key Concepts Covered
During this task, I explored the following concepts:
* **Overfitting:** Why models shouldn't memorize training data.
* **Train-Test Split:** The standard practice for validating models.
* **Confusion Matrix:** Understanding Type I (False Positive) and Type II (False Negative) errors.
* **
