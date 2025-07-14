# SalaryPrediction
# 💼 Salary Prediction Model using IBM Watson AutoAI

This project predicts the **salary of an individual** based on various job and personal attributes using IBM Watson AutoAI. The model was trained and deployed on IBM Cloud using XGBoost Regressor with automatic feature engineering, hyperparameter tuning, and evaluation.

---

## ✨ Features

- 🔍 Predict salary based on multiple input parameters
- 🤖 Uses IBM Watson AutoAI for automated model building
- 📊 Model trained on XGBoost Regressor with highest performance
- 🚀 Deployed online using IBM Watson Machine Learning (cloud-based)
- 📈 Visual pipeline and evaluation metrics
- 🔒 API-ready model for real-world prediction use

---

## 🧠 Input Parameters

The model takes the following features as input:

| Feature Name        | Description                                         |
|---------------------|-----------------------------------------------------|
| `ID`                | Unique identifier for each data entry              |
| `education_level`   | Level of education (e.g., Bachelor's, Master's)     |
| `years_experience`  | Total years of professional experience              |
| `job_title`         | Current job title                                   |
| `industry`          | Industry of employment (e.g., Tech, Finance)        |
| `location`          | City/Region where the individual works             |
| `company_size`      | Size of the organization (e.g., Small, Medium)      |
| `certifications`    | Number of professional certifications               |
| `age`               | Age of the individual                               |
| `working_hours`     | Weekly working hours                                |
| `crucial_code`      | A categorical code for criticality or job level     |

---

## 🎯 Target Variable

- `salary`: The annual salary to be predicted.

---

## 🛠 Technologies Used

| Component             | Tech |
|-----------------------|------|
| ML Model              | XGBoost Regressor |
| Model Training        | IBM Watson AutoAI |
| Deployment Platform   | IBM Watson Machine Learning |
| Programming Language  | Python |
| Notebook Platform     | Google Colab / Jupyter |
| Hosting               | IBM Cloud |

---

## 🧬 AutoAI Training Flow

AutoAI performed automatic:
- Dataset splitting
- Preprocessing
- Model and algorithm selection
- Hyperparameter tuning
- Pipeline evaluation

### 📍 Progress Map

![Progress Map](https://github.com/tanishkagoyal13/SalaryPrediction/raw/main/progress%20map.png)


---

## 📊 Evaluation: Metric Chart

AutoAI evaluated 8 pipelines (P1 to P8). Pipeline P4 performed best with the highest explained variance and lowest errors.

![Metric Chart](https://github.com/tanishkagoyal13/SalaryPrediction/raw/main/metric%20chart.png)

---

## 🌐 Relationship Map

A graphical representation of relationships between data, algorithms, pipelines, and transformers.

![Relationship Map](https://github.com/tanishkagoyal13/SalaryPrediction/raw/main/relationship%20map.png)

---

## 📂 Project Structure



