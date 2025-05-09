# HR Analytics - Predict Employee Attrition

## 🎯 Objective
Use analytics and machine learning to understand the main causes of employee resignation and predict future attrition risk.

---

## 🧰 Tools & Technologies

- **Python (Jupyter Notebook)**  
  - Libraries: `pandas`, `seaborn`, `scikit-learn`, `shap`
- **Power BI**  
  - Interactive dashboard for visualizing attrition patterns
- **Machine Learning**  
  - Logistic Regression or Decision Tree Classifier
- **Model Evaluation**  
  - Accuracy report, confusion matrix, and classification report delivered separately

---

## 📁 Project Structure

├── hr_data_project1.ipynb # EDA, preprocessing, model training, SHAP analysis
├── model_evaluation.ipynb # Separate notebook for accuracy, confusion matrix & classification report
├── HR_Dashboard.pbix # Power BI report (Attrition Rate by Department, Salary Band, etc.)
├── model_accuracy_report.txt # Text report of model accuracy and classification metrics
├── confusion_matrix.png # Visual plot of confusion matrix
├── README.md # Project documentation (this file)


---

## 📊 Key Steps

### 1. Exploratory Data Analysis (EDA)
- Attrition by Department
- Salary band impact
- Promotions and attrition correlation

### 2. Classification Model
- Logistic Regression or Decision Tree
- Predicts which employees are at risk of attrition

### 3. Model Evaluation
- Accuracy, precision, recall, F1-score
- Confusion matrix to visualize prediction performance

### 4. Explainability
- SHAP value analysis to explain feature contributions

### 5. Power BI Dashboard
- Department-wise attrition rates
- Salary & promotion visuals
- Interactive filters and color-coded indicators

---

## 📦 Deliverables

| File | Description |
|------|-------------|
| `hr_data_project1.ipynb` | Main Python notebook (EDA, modeling, SHAP) |
| `model_evaluation.ipynb` | Accuracy report, confusion matrix, and classification metrics |
| `HR_Dashboard.pbix` | Interactive Power BI dashboard |
| `model_accuracy_report.txt` | Text-based evaluation report |
| `confusion_matrix.png` | Image of the confusion matrix heatmap |

---

## 🚀 How to Run

### 🔹 Jupyter Notebook

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/hr-analytics-attrition.git
   cd hr-analytics-attrition
