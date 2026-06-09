# 24JR1A05H5-JOSEPH-NITHISH_WEEK-3_DAY-1_ML_FUNDAMENTALS_ASSIGNMENT-1-
# Week 3 Day 1 — ML Fundamentals: Student Performance Prediction

## 📌 Overview
This project is part of the AIML Internship Week 3 Day 1 Assignment.
It demonstrates a complete Machine Learning workflow using Linear Regression
to predict student marks based on Study Hours, Attendance, and Assignments.

## 📁 Repository Structure

week3-day1-ml-fundamentals/
│
├── student_performance.csv   → Dataset (12 student records)
├── assignment.ipynb          → Main Jupyter Notebook (all code)
├── ml_workflow.txt           → ML Workflow documentation
├── answers.txt               → Research activity answers
├── screenshots/
│   ├── plot1.png             → Study Hours vs Marks
│   ├── plot2.png             → Attendance vs Marks
│   ├── plot3.png             → Assignments vs Marks
│   ├── plot4.png             → Regression Line
│   └── plot5.png             → Predicted Marks Trend
└── README.md                 → This file

## 📊 Dataset

**File:** `student_performance.csv`

| Column | Type | Description |
|--------|------|-------------|
| Study_Hours | int | Hours studied per day |
| Attendance | int | Attendance percentage |
| Assignments | int | Assignments completed |
| Marks | int | Target variable (to predict) |

- Total Records: 12 students
- Features: 3 (Study_Hours, Attendance, Assignments)
- Label: Marks

## 🎯 Assignment Parts Completed

| Part | Topic | Marks |
|------|-------|-------|
| Part 1 | Dataset Exploration | 10 |
| Part 2 | Features and Label | 10 |
| Part 3 | ML Workflow Documentation | 10 |
| Part 4 | Train-Test Split | 10 |
| Part 5 | Train Linear Regression Model | 10 |
| Part 6 | Predictions on New Data | 10 |
| Part 7 | Actual vs Predicted Comparison | 10 |
| Part 8 | Model Evaluation (MAE & R²) | 10 |
| Part 9 | Data Visualization (5 Plots) | 15 |
| Part 10 | Student Research Activity | 15 |
| Bonus | House Price Prediction | +10 |
| **Total** | | **110** |

## 🔧 Features and Label

**Features (X) — Inputs:**
- `Study_Hours` — Hours studied per day
- `Attendance`  — Percentage of classes attended
- `Assignments` — Number of assignments completed

**Label (y) — Output:**
- `Marks` — Final marks to predict

## 🤖 Algorithm Used

**Linear Regression** from `sklearn.linear_model`

Formula:
- `m1, m2, m3` → Coefficients (learned from training data)
- `b`           → Intercept (bias term)

## ⚙️ ML Workflow

1. **Data Collection**   → Created student dataset with 12 records
2. **Data Cleaning**     → Checked for missing values (none found)
3. **Feature Selection** → Selected 3 features, 1 label
4. **Train-Test Split**  → 80% training, 20% testing
5. **Model Training**    → LinearRegression().fit(X_train, y_train)
6. **Testing**           → model.predict(X_test)
7. **Evaluation**        → MAE and R² Score
8. **Prediction**        → Predicted marks for new students
-

## 📈 Model Evaluation Results

| Metric | Value |
|--------|-------|
| Algorithm | Linear Regression |
| Train/Test Split | 80% / 20% |
| MAE | Run notebook to see |
| R² Score | Run notebook to see |

---

## 📊 Visualizations

| Plot | Title | Type |
|------|-------|------|
| plot1.png | Study Hours vs Marks | Scatter Plot |
| plot2.png | Attendance vs Marks | Scatter + Hover |
| plot3.png | Assignments vs Marks | Colored Scatter |
| plot4.png | Regression Line | Scatter + Line |
| plot5.png | Predicted Marks Trend (1–15 hrs) | Line Chart |

---

## 🌟 Bonus — House Price Prediction

**Dataset:** 20 house records  
**Features:** AreaSqFt, NumBedrooms, DistanceFromCity_km  
**Label:** Price_Lakhs  
**Algorithm:** Linear Regression  

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Create a new notebook
3. Copy all cells from `assignment.ipynb`
4. Run `Runtime → Run All`
5. Download output files from the Files panel

**Required Libraries:**
```bash
pip install pandas numpy scikit-learn plotly
```

---

## 📦 Libraries Used

| Library | Purpose |
|---------|---------|
| pandas | Data loading and manipulation |
| numpy | Numerical operations |
| scikit-learn | ML model, split, evaluation |
| plotly | Interactive visualizations |

---

## 👤 Author

**Name:** M.JOSEPH NITHISH -24JR1A05H5
**Internship:** ML Internship — Week 3 Day 1  
**Topic:** Machine Learning Fundamentals  
