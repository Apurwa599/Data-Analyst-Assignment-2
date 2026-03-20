## Data-Analyst-Assignment-2
### 📊 Instructor Effectiveness Modeling (EdTech Platform)

### 📌 Project Overview
This project focuses on analyzing and modeling **instructor effectiveness** using data from an EdTech platform. The goal is to evaluate instructor performance based on learner outcomes, engagement, and feedback, and to build a machine learning model that classifies instructors into effectiveness tiers.

### 🎯 Objectives
* Perform **Exploratory Data Analysis (EDA)**-to understand the dataset
* Define an **Instructor Effectiveness Score**
* Aggregate batch-level data to **instructor-level insights**
* Build a **Machine Learning model**-to predict effectiveness categories
* Evaluate model performance
* Interpret key factors influencing instructor effectiveness
  
### 📂 Dataset
The dataset contains ~2000 records with features related to:

* Learner performance (quiz scores, completion rates)
* Engagement metrics
* Feedback ratings

### 🛠️ Tech Stack

* **Python**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning

### 🔍 Exploratory Data Analysis (EDA)
EDA was performed to:

* Understand feature distributions
* Detect missing values and outliers
* Analyze relationships between variables using correlation heatmaps
* Visualize key metrics like quiz scores and feedback

### 🧮 Feature Engineering

* Created an **Instructor Effectiveness Score** based on:

  * Quiz performance
  * Engagement
  * Feedback ratings
* Aggregated batch-level metrics to instructor-level data

---

## 🤖 Model Building

* Model Used: **Random Forest Classifier**
* Steps:

  1. Train-test split
  2. Feature scaling
  3. Model training
  4. Prediction on test data

---

## 📈 Model Evaluation

* Evaluated using:

  * **Classification Report**
  * **Confusion Matrix**
* Metrics:

  * Accuracy
  * Precision
  * Recall
  * F1-score

---

## 💡 Key Insights

* Feedback scores strongly influence instructor effectiveness
* Higher engagement correlates with better learner outcomes
* Certain performance metrics are strong predictors of instructor success

---

## 🚀 How to Run the Project

1. Clone the repository

   ```bash
   git clone <your-repo-link>
   ```

2. Install dependencies

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Run the notebook

   ```bash
   jupyter notebook
   ```

---

## 📌 Future Improvements

* Use advanced models like **XGBoost or LightGBM**
* Hyperparameter tuning for better performance
* Deploy model using **Streamlit**
* Add real-time instructor evaluation dashboard

---

## 👩‍💻 Author

**Apurwa Khare**
MCA (AI & ML) | Data Science & Machine Learning Enthusiast

---

## 📎 Notes

This project is part of an **EdTech analytics assignment**, demonstrating skills in:

* Data analysis
* Machine learning
* Business insight generation

---
