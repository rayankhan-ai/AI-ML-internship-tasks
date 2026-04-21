# 🧪 Task 1: Iris Dataset Analysis

## 🎯 Objective
To explore and visualize the Iris dataset in order to understand feature relationships, distributions, and detect outliers.

---

## 📊 Dataset Used
- **Name:** Iris Dataset  
- **Source:** Local CSV file  
- **Description:**  
  The dataset contains measurements of iris flowers:
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
  - Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Steps Performed

### 🔹 Data Loading & Inspection
- Loaded dataset using pandas
- Checked:
  - Shape of dataset
  - Column names
  - First few rows (.head())
  - Dataset info (.info())
  - Statistical summary (.describe())
- Dropped unnecessary column (Id)

---

### 🔹 Data Visualization

#### 📌 Scatter Plots
- Sepal Length vs Sepal Width  
- Petal Length vs Petal Width  

**Findings:**
- Setosa is clearly separable
- Petal features provide better classification

---

#### 📌 Histograms
- Distribution of all numerical features using seaborn

**Findings:**
- Sepal features are normally distributed
- Petal features show bimodal distribution

---

#### 📌 Box Plots
- Used to detect outliers per species

**Findings:**
- Sepal Width contains most outliers
- Petal features are clean with minimal outliers

---

## 📈 Key Results & Observations
- Petal Length and Petal Width are highly important features
- Clear class separation using petal features
- Dataset is mostly clean with few outliers

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 📂 Project Structure
task1_iris_analysis/
│── iris_analysis.py  
│── README.md  

---

## 🚀 Conclusion
This task helped in understanding how to perform exploratory data analysis (EDA), visualize datasets, and extract meaningful insights using Python libraries.
