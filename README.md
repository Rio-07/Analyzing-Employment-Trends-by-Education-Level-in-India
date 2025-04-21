# 📊 Analyzing Employment Trends by Education Level in India

This project explores the relationship between education levels and employment patterns across Indian states using Census data. The objective is to identify how education—particularly graduate-level education—impacts the number of main workers (employed individuals) in various regions.

---

## 🧠 Objectives

- Clean and preprocess Census data
- Group data by state to find aggregate education and employment stats
- Visualize trends between education levels and employment
- Apply Linear Regression to analyze correlation between graduate education and main workers
- Identify patterns that can inform policymakers or researchers

---

## 📁 Dataset

The data used in this project is derived from **India's Census** data, with attributes including:
- `State/UT`
- `Literate`, `Illiterate`
- `Primary_Education`, `Secondary_Education`
- `Graduate_Education`, `Other_Education`
- `Main_Workers`, `Marginal_Workers`, `Non_Workers`

---

## 🔧 Technologies Used

- **Python 3**
- **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **scikit-learn** for Linear Regression
- **Jupyter Notebook** for exploratory analysis

---

## 🧪 Machine Learning Model

- **Model Used**: Linear Regression
- **Target**: `Main_Workers`
- **Feature**: `Graduate_Education`
- **Metric**: R-squared (Coefficient of Determination)

```python
R² Score ≈ 0.82  # Example output from model.score(X, y)
