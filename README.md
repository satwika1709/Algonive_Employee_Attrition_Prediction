# Algonive_Employee_Attrition_Prediction

---

# Employee Attrition Prediction using Machine Learning

##  Project Overview

This project aims to predict employee attrition (whether an employee will leave the company) using Machine Learning techniques. The goal is to help organizations identify at-risk employees and take preventive measures to improve retention.

---

##  Dataset

The project uses the IBM HR Analytics Employee Attrition dataset.

* Total Records: 1470 employees
* Target Variable: Attrition (Yes/No)
* Features include age, job role, salary, satisfaction levels, work experience, and more.

---

## Steps Performed

1. Data Loading and Exploration
2. Data Cleaning (removed irrelevant columns)
3. Feature Encoding (converted categorical variables to numeric)
4. Train-Test Split using stratified sampling
5. Feature Scaling (for Logistic Regression)
6. Model Training
7. Model Evaluation using:

   * Accuracy
   * Precision
   * Recall
   * F1 Score
   * ROC-AUC

---

##  Models Implemented

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Balanced Logistic Regression
5. Tuned Decision Tree
6. Tuned Random Forest

---

##  Final Model Selection

Balanced Logistic Regression performed the best in detecting employees likely to leave.

Since the dataset is imbalanced, recall was prioritized over overall accuracy. The final model effectively identifies high-risk employees while maintaining good overall performance.

---

##  Key Insights

* Employees with higher job satisfaction are less likely to leave.
* More total working years reduces attrition risk.
* Strong relationship with the manager improves retention.
* Overtime work increases the likelihood of attrition.

---

##  Business Impact

This model can help HR departments:

* Identify employees at risk of leaving
* Improve employee satisfaction strategies
* Reduce recruitment and training costs
* Make data-driven workforce decisions

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

##  How to Run

1. Install required libraries:
   pip install -r requirements.txt

2. Run the notebook:
   Open Employee_Attrition_Prediction.ipynb

---

##  Conclusion

Machine Learning can effectively predict employee attrition. Balanced Logistic Regression was selected as the final model due to its strong recall and balanced performance. This project demonstrates how data-driven solutions can improve HR decision-making.

---

