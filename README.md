# 📊 A/B Testing Analysis – ENIAC Project

A data analysis project focused on evaluating performance using **A/B testing techniques**.
This project demonstrates how data can be used to support **business decisions** and measure impact.

---

## 🚀 Project Overview

In this project, we analyze two versions (A and B) of a product to determine which one performs better based on user behavior.

### 🎯 Objectives:

* Compare performance between two groups
* Calculate key metrics (conversion rate, lift)
* Extract insights to support decision-making

---

## 🧰 Tech Stack

* **Python** (Pandas, NumPy)
* **Data Visualization** (Matplotlib)
* **Google Colab**
* **GitHub**

---

## 📊 Key Steps

1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Conversion rate calculation
4. Performance comparison (A vs B)
5. Visualization of results
6. Business interpretation

---

## 📈 Key Metrics

* Conversion Rate
* Performance Lift (%)
* User Behavior Analysis

---

## 🔍 Example Code

```python
conversion_A = df[df["group"] == "A"]["converted"].mean()
conversion_B = df[df["group"] == "B"]["converted"].mean()

lift = ((conversion_B - conversion_A) / conversion_A) * 100
print(f"Lift: {lift:.2f}%")
```

---

## 📌 Insights

* Identified which version performs better
* Quantified improvement between variants
* Provided clear recommendations

---

## 🎯 Project Impact

This project highlights:

* Strong analytical thinking
* Ability to interpret data
* Data-driven decision-making skills

---

## 👩🏽‍💻 Author

**Tatiana Tchouakam Chouacheu**
Data & Cloud Engineer in Training

GitHub: https://github.com/TatianaTchouakam

---

## ⭐ If you like this project

Feel free to give it a ⭐ and explore more data projects!
