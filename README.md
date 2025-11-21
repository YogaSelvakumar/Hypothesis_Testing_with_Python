
# 🚕 Taxi Fare Hypothesis Testing Project

This project focuses on analyzing taxi trip data to investigate whether there is a **statistically significant difference in fare amounts between card and cash payments**. The workflow includes exploratory data analysis, feature engineering, outlier removal, visualization, and a two-sample t-test.

---

## 📌 Objective
To determine if **payment type (Card vs Cash)** has an effect on the **fare amount** using **A/B hypothesis testing**.

---

## 🧠 Hypothesis Statement

### Null Hypothesis (H₀):
There is **no significant difference** in mean fare amount between **card** and **cash** payments.

### Alternative Hypothesis (H₁):
There **is a significant difference** in mean fare amount between **card** and **cash** payments.

---

## 📊 Dataset Overview
| Column | Description |
|--------|-------------|
| passenger_count | Number of passengers in ride |
| trip_distance | Distance traveled (miles/km depending dataset) |
| payment_type | Card or Cash |
| fare_amount | Fare charged for the trip |
| duration | Trip duration |

---

## 🔧 Tech Stack & Tools
| Area | Tools |
|-------|--------|
| Analysis | Python (Pandas, NumPy, SciPy) |
| Visualization | Matplotlib |
| Hypothesis Testing | Two-sample T-test |
| Documentation | PDF report, Visual charts| Jupyter Notebook |

---

## 🧹 Data Preparation
- Cleaned missing & inconsistent records
- Performed **feature engineering**
- Applied **IQR method to remove outliers**
- Visualized category distributions

---

## 📈 Key Visuals
📍 Payment Type Distribution  
📍 Outlier Removal Boxplot  
📍 Passenger Count vs Payment Type

_(All visuals are included in the PDF report)_
https://github.com/YogaSelvakumar/Hypothesis_Testing_with_Python/blob/main/Hypothesis_Testing_Detailed_Report%20(2).pdf.pdf
---

## 🧪 Hypothesis Testing Results

The p-value was extremely small (≈ 2.85e-12), which is far below the 0.05 threshold, indicating a statistically significant difference in fare amounts between card and cash payments.
🟦 Card users tend to have slightly higher fare amounts than cash users.
