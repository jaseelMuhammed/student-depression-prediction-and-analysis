
---

## 🔍 Objective

To analyze patterns and predict student depression levels based on academic pressure, sleep patterns, study satisfaction, dietary habits, and other psychological indicators, and visualize these insights interactively.

---

## 📊 Dashboard Overview

The Power BI Dashboard includes:

| Section                  | Description |
|--------------------------|-------------|
| **KPI Cards**            | Total Students, % Depressed, High Pressure Count, etc. |
| **Depression by Gender** | Donut chart showing gender-based depression distribution |
| **Study Hours vs CGPA**  | Line chart split by gender |
| **Depression by City**   | Map view of CGPA and depression status |
| **Table View**           | Academic pressure, sleep, and satisfaction details |
| **Dietary Habits**       | Bar chart of diet type and student count |
| **Filters**              | City, Gender, Degree, Depression |

> 📌 **Insight Example**: A strong correlation exists between study satisfaction and depression levels, along with notable patterns in gender-wise CGPA.

---

## 🧠 Machine Learning Pipeline (Notebook)

Implemented using Python with Scikit-learn, Pandas, and Seaborn:

### 🔹 Steps:

1. **Data Preprocessing**
   - Missing value handling
   - Encoding categorical variables
   - Feature engineering

2. **Exploratory Data Analysis (EDA)**
   - Depression % by gender, study hours, dietary habits
   - Correlation heatmaps and distributions

3. **Model Building**
   - Algorithms: Logistic Regression, Random Forest, GradientBoosting
   - Accuracy and confusion matrix comparisons
   - Feature importance visualization

4. **Evaluation**
   - Model with best performance chosen based on F1-score and ROC-AUC

---

## 📦 Tech Stack

| Area               | Tools Used |
|--------------------|------------|
| Language           | Python (Pandas, NumPy, Scikit-learn) |
| Visualization      | Power BI, Seaborn, Matplotlib         |
| ML Algorithms      | Gradient Boosting, Logistic Regression, Random Forest |
| Dashboard          | Power BI Desktop                      |


---

## 📌 Key Insights

- Students with **poor sleep and low satisfaction** had significantly higher depression likelihood.
- **Female students** reported slightly higher CGPA but also showed more symptoms of depression.
- **Academic pressure** is a key predictor in the model's feature importance ranking.

---

## 🚀 Getting Started

### Clone the repo
```bash
git clone https://github.com/yourusername/student-depression-dashboard.git
cd student-depression-dashboard

