# ❤️ Task 3: Heart Disease Prediction

## 🎯 Objective
To build a machine learning model that predicts whether a person is at risk of heart disease based on medical attributes.

---

## 📊 Dataset Used
- **Name:** Heart Disease Dataset (heart.csv)
- **Source:** Kaggle / UCI Repository
- **Description:**
  The dataset contains medical information such as:
  - Age, Gender
  - Blood Pressure
  - Cholesterol
  - Chest Pain Type
  - Heart Rate
  - ST Depression
  - Target (Heart Disease: 0 = No, 1 = Yes)

---

## ⚙️ Steps Performed

### 🔹 Data Loading & Exploration
- Loaded dataset using pandas
- Checked shape, structure, and missing values
- Removed duplicate rows

---

### 🔹 Data Cleaning
- Renamed columns for better readability
- Handled duplicate records
- Checked statistical summary

---

### 🔹 Outlier Handling
- Detected outliers using box plots
- Applied IQR method to cap extreme values

---

### 🔹 Data Visualization
- Correlation heatmap to understand feature relationships
- Box plots to analyze outliers

---

### 🔹 Feature Engineering
- Categorical variables encoded using One-Hot Encoding
- Numerical features scaled using StandardScaler

---

### 🔹 Model Building

#### 1. Logistic Regression
- Used for binary classification
- Evaluates probability of heart disease

#### 2. Decision Tree Classifier
- Tree-based model for classification
- Captures complex patterns in data

---

## 📈 Model Evaluation

### Metrics Used:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

### Results:
- Logistic Regression: Good baseline performance
- Decision Tree: Better flexibility and performance
- Final comparison showed Decision Tree performed better

---

## 📊 Visualizations
- Correlation heatmap
- Confusion matrices for both models
- Accuracy comparison bar chart

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Project Structure
task3_heart_disease/
│── heart_disease.py  
│── README.md  

---

## 🚀 Conclusion
This project demonstrates a complete machine learning pipeline including data cleaning, preprocessing, visualization, model training, and evaluation for heart disease prediction.
