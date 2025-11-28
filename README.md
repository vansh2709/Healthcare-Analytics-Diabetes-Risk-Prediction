# Healthcare Analytics: Employee Diabetes Risk Prediction

## Project Overview

This project analyzes healthcare data to **predict diabetes risk among employees** using **Python and Random Forest**, with insights visualized via **Power BI dashboards**. The goal is to help HR teams take **proactive, data-driven actions** to improve employee well-being and reduce healthcare costs.

---

## Business Problem

Diabetes in the workforce can lead to:

* Increased healthcare expenses
* Reduced productivity
* Higher absenteeism

This project identifies employees at higher risk of diabetes to enable **early intervention, targeted wellness programs, and better resource allocation**.

---

## Technologies Used

* **Python**: Data cleaning, EDA, feature engineering, Random Forest model
* **Pandas & NumPy**: Data manipulation
* **Seaborn & Matplotlib**: Data visualization
* **Scikit-learn**: Machine learning and model evaluation
* **Power BI**: Interactive dashboards for HR insights

---

## Dataset

Synthetic healthcare dataset with 500 patient records, including:

* Age, Gender, BMI, Blood Pressure, Cholesterol
* Smoking status, Hospital Visits, Treatment Costs
* Target variable: `Has_Diabetes` (0 = No, 1 = Yes)

---

## Project Workflow

1. **Exploratory Data Analysis (EDA)** – Understand distributions, correlations, and patterns
2. **Feature Engineering** – BMI categories, age groups, interaction features
3. **Data Preprocessing** – Encoding categorical features, scaling numeric features
4. **Predictive Modeling** – Random Forest classifier with hyperparameter tuning
5. **Model Evaluation** – Accuracy, Precision, Recall, F1 Score, Feature Importance
6. **Insights & Recommendations** – HR-focused interpretation of risk factors
7. **Power BI Dashboard** – Interactive visualization of diabetes risk and key metrics

---

## Key Findings

* **Major Risk Factors:** High treatment cost, blood pressure, BMI, age
* **Model Performance:**

  * Accuracy: X%
  * Recall: 4% (focus on early detection improvement)
  * Precision: 33% (reducing false positives)
* **Actionable HR Recommendations:**

  * Targeted wellness programs (weight management, screenings, education)
  * Proactive monitoring of high-risk employees
  * Employee awareness campaigns

---

## Repository Contents

```
/data
    healthcare_data.csv           # Dataset
/notebooks
    healthcare_advanced_rf.ipynb  # EDA + Random Forest model
/reports
    healthcare_predictions.csv     # Model predictions
README.md                           # Project description
```

---

## Impact

This project demonstrates **how data analytics can transform employee health management**. HR teams can leverage these insights to **design proactive wellness programs, reduce healthcare costs, and improve workforce productivity**.

---

## Future Work

* Improve model recall by **adding more data and features**
* Explore alternative models (XGBoost, Gradient Boosting)
* Expand dashboards to track **trends over time**

---

## Contact

For questions or collaboration, reach out at v2056779@gmail.com / https://www.linkedin.com/in/vansh-verma-ab318b304/
