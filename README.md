<h1 align="center">🏥 Health Tracking System</h1>
<p align="center">
  <strong>Supervised Machine Learning Project for Health Risk Classification</strong>
</p>

---

## 🚀 About The Project

Health Tracking System is a Machine Learning-powered classification system designed to predict whether an individual is:

- ✅ Healthy  
- ⚠️ At Higher Health Risk  

The project supports data-driven healthcare analysis by identifying individuals who may require closer monitoring or medical intervention.

---

## 📊 Project Objective

To build a supervised machine learning model that:

- Classifies individuals based on health indicators
- Minimizes false negatives (important in healthcare)
- Identifies influential health-related features
- Supports research and risk-based stratification

---

## 📁 Dataset Overview

The dataset contains records of **9,800 individuals** with numerical and categorical health features.

### Key Features

| Feature | Description |
|----------|-------------|
| Age | Age in years |
| BMI | Body Mass Index |
| Blood_Pressure | Systolic BP |
| Cholesterol | Cholesterol level |
| Glucose_Level | Blood glucose level |
| Heart_Rate | Resting heart rate |
| Sleep_Hours | Average sleep duration |
| Exercise_Hours | Exercise duration |
| Water_Intake | Daily water intake |
| Stress_Level | Stress score (1–10) |
| Smoking | 1 = Smoker, 0 = Non-smoker |
| Alcohol | 1 = Yes, 0 = No |
| Diet | Encoded diet category |
| MentalHealth | Mental health score |
| PhysicalActivity | Physical activity level |
| MedicalHistory | Prior medical conditions |
| Allergies | Known allergies |
| Diet_Type__Vegan | One-hot encoded |
| Diet_Type__Vegetarian | One-hot encoded |
| Blood_Group_AB | One-hot encoded |
| Blood_Group_B | One-hot encoded |
| Blood_Group_O | One-hot encoded |
| Target | Health classification label |

---

## 🧠 Machine Learning Workflow

1️⃣ Data Cleaning & Preprocessing  
2️⃣ Exploratory Data Analysis (EDA)  
3️⃣ Feature Encoding & Scaling  
4️⃣ Train-Test Split  
5️⃣ Model Training  
6️⃣ Model Evaluation  
7️⃣ Performance Comparison  

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## 📊 Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix Heatmap

Medical models prioritize:
> High Recall (to reduce missed high-risk individuals)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Ishu335/Health-Tracking-System.git
cd Health-Tracking-System
