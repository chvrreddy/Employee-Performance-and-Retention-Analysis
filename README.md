# 📌 Employee Performance and Retention Analysis

## 📖 Project Overview
This project analyzes employee performance and attrition trends, builds machine learning and deep learning models, and derives actionable insights for improving workforce retention and performance.  

Key objectives:
- Analyze employee data using statistics & probability.  
- Predict attrition (classification).  
- Predict performance scores (regression).  
- Provide insights & recommendations to HR managers.  

---

## 📂 Dataset
- **File:** `employee_data.csv`  
- **Size:** 100 employees × 8 features  
- **Features:**
  - `EmployeeID` – Unique identifier  
  - `Name` – Employee name  
  - `Age` – Employee age  
  - `Department` – Department name  
  - `Salary` – Annual salary  
  - `YearsAtCompany` – Tenure in years  
  - `PerformanceScore` – Performance rating (numeric)  
  - `Attrition` – Target variable (`Yes`/`No`)  

---

## 🛠️ Steps in the Project

### Step 1: Data Collection & Preprocessing
- Loaded dataset and cleaned column names.  
- Removed duplicates and normalized categorical variables.  
- Encoded target variable (`Attrition`).  

### Step 2: Exploratory Data Analysis (EDA)
- Histograms, boxplots, and heatmaps used for visualization.  
- Found outliers in `Salary` and `YearsAtCompany`.  
- Higher attrition in **HR** and **Sales** departments.  

### Step 3: Probability & Statistical Analysis
- Overall attrition rate ≈ X% (replace with your run result).  
- Low performers had higher attrition probability.  
- ANOVA confirmed performance differs across departments.  

### Step 4: Feature Engineering & Encoding
- Encoded categorical features (`Department`, `Attrition`).  
- Scaled numeric features (`Age`, `Salary`, `YearsAtCompany`, `PerformanceScore`) using Standardization & Min-Max Scaling.  

### Step 5: Attrition Prediction (Classification)
- Models: Logistic Regression, Random Forest, Neural Network.  
- Metrics: Accuracy, Precision, Recall, F1-Score.  
- Random Forest & Neural Network outperformed Logistic Regression.  

### Step 6: Performance Prediction (Regression)
- Built Linear Regression model → moderate fit.  
- Neural Network regression → better prediction with lower MSE.  

### Step 7: Deep Learning for Performance
- Feedforward Neural Network trained using **MSE** loss.  
- Predicted employee performance more accurately than linear regression.  

### Step 8: Deep Learning for Attrition
- Neural Network classifier trained with **Binary Cross-Entropy**.  
- Evaluated with Accuracy, Precision, Recall, F1.  
- Visualized using Confusion Matrix.  

### Step 9: Insights & Recommendations
- **Key factors for performance:** Salary, Tenure, Department.  
- **High-risk attrition groups:** HR and Sales.  
- Recommendations: retention programs, training for low performers, career progression paths, engagement programs.  

### Step 10: Visualization & Reporting
- Line Plot: Performance trends with tenure.  
- Bar Chart: Department-wise attrition rates.  
- Scatter Plot: Salary vs Performance.  
- Detailed report prepared with findings & recommendations.  

---

## 📊 Visualizations
- 📈 **Line Plot**: Average performance vs. years at company.  
- 📊 **Bar Chart**: Attrition rate by department.  
- 🔵 **Scatter Plot**: Salary vs performance score (highlighting attrition).  
- 🔲 **Confusion Matrix**: Model classification performance.  

---

## 📌 Recommendations
- Focus retention strategies on **HR & Sales** departments.  
- Provide **training & mentorship** for low performers.  
- Offer **career growth opportunities** for mid-tenure employees.  
- Implement **data-driven HR dashboards** for proactive monitoring.  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Scikit-learn** (Logistic Regression, Random Forest, Scaling, Encoding)  
- **TensorFlow / Keras** (Neural Networks for regression & classification)  
- **SciPy** (ANOVA & statistical tests)  

---

## 📑 Deliverables
- Cleaned dataset: `employee_data_cleaned.csv`  
- Jupyter Notebook / Colab Notebook with step-by-step implementation.  
- README file (this document).  
- Final project report (PDF/Markdown).  

---

## 🚀 How to Run
1. Clone the repo or download the files.  
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
