# 📊 Types of Statistics

Statistics is the backbone of data-driven decision-making. Whether you're analyzing financial markets, evaluating business performance, or building machine-learning models, statistics provides the mathematical tools to transform raw data into actionable insights.

This section introduces the **two core branches of statistics**—Descriptive and Inferential—supported with explanations and clean examples.

---

# 1️⃣ Descriptive Statistics

Descriptive statistics summarize and organize data to make it easy to understand.  
These techniques **do not** make predictions—they only describe *what the data shows*.

### 🔧 Tools Used
- **Measures of Central Tendency:** Mean, Median, Mode  
- **Measures of Spread:** Range, Variance, Standard Deviation  
- **Data Visualization:** Histograms, Bar Charts, Box Plots  
- **Tabular Representation:** Frequency tables, cross-tabs  

---

## 📘 Example Dataset

Scores of 10 students:

| Student | Score |
|---------|-------|
| A | 85 |
| B | 90 |
| C | 78 |
| D | 92 |
| E | 88 |
| F | 76 |
| G | 95 |
| H | 89 |
| I | 84 |
| J | 91 |

### 📐 Summary Measures
- **Mean:** 86.8  
- **Median:** 88.5  
- **Mode:** None (all unique)  
- **Standard Deviation:** ≈ 6.3  

---

## 📊 Sample ASCII Histogram  
*(Markdown-safe visualization that works on GitHub)*


This quick visual shows a concentration around 85–90.

---

# 2️⃣ Inferential Statistics

Inferential statistics use samples to draw **conclusions about a population**.  
This is essential when it’s impossible or impractical to measure the entire population.

### ⚙️ Common Techniques
- **Hypothesis Testing** (A/B testing, t-tests, chi-square tests)
- **Confidence Intervals**
- **Regression Analysis**
- **ANOVA**
- **Sampling Methods**

---

## 📘 Example: Light Bulb Lifespan Study

A factory tests **50 sample bulbs** to estimate the average lifespan of all bulbs:

- Sample mean = **980 hours**  
- Sample standard deviation = **20 hours**  
- Population mean = unknown  

### 🔍 95% Confidence Interval

\[
CI = \bar{x} \pm Z \frac{s}{\sqrt{n}} = 980 \pm 1.96 \frac{20}{\sqrt{50}}
\]

\[
CI = 980 \pm 5.5
\]

### 🎯 Interpretation
We are **95% confident** the true population mean lifespan is between:

> **974.5 hours and 985.5 hours**

---

# 🧾 Summary Comparison Table

| Type of Statistics | Purpose | Key Tools | Example |
|-------------------|---------|-----------|----------|
| **Descriptive** | Describe and summarize data | Mean, Median, SD, charts, tables | Student score summary |
| **Inferential** | Make predictions about a population | Hypothesis tests, CI, regression | Light bulb lifespan estimation |

---

# 📌 Key Takeaway

Descriptive statistics help you **understand what happened**.  
Inferential statistics help you **predict what will happen**.

Both are essential pillars for analytics, machine learning, econometrics, and data-driven decision-making.

---
