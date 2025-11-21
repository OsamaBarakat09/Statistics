# Types of Statistics

Statistics is the science of collecting, analyzing, interpreting, and presenting data. Broadly, it is divided into **Descriptive Statistics** and **Inferential Statistics**. Understanding these types is fundamental for data analysis, predictive modeling, and decision-making.

---

## 1. Descriptive Statistics

Descriptive statistics **organize, summarize, and present data** in a meaningful way. This is typically done through:

- **Tables** – arranging data in rows and columns for easy reference.
- **Graphs** – visual representation using bar charts, histograms, pie charts, etc.
- **Summary measures** – numerical summaries such as mean, median, mode, variance, and standard deviation.

### Example

Suppose we have the exam scores of 10 students:

| Student | Score |
|---------|-------|
| A       | 85    |
| B       | 90    |
| C       | 78    |
| D       | 92    |
| E       | 88    |
| F       | 76    |
| G       | 95    |
| H       | 89    |
| I       | 84    |
| J       | 91    |

- **Mean (Average):**  
\[
\text{Mean} = \frac{85 + 90 + 78 + 92 + 88 + 76 + 95 + 89 + 84 + 91}{10} = 86.8
\]

- **Median (Middle Value):** 88.5  
- **Mode (Most Frequent):** No repeated value → Mode = None  
- **Standard Deviation (Spread of data):** ≈ 6.3

**Visual Example:**  
A histogram could show the distribution of scores, giving a quick sense of performance.

---

## 2. Inferential Statistics

Inferential statistics **use sample data to make predictions or decisions about a population**. Unlike descriptive statistics, which only describe, inferential statistics allow us to **generalize results** and **estimate uncertainty**.

Common methods include:

- **Hypothesis testing** – e.g., testing if a new drug is effective.  
- **Confidence intervals** – estimating population parameters with a margin of error.  
- **Regression analysis** – predicting outcomes based on input variables.  
- **ANOVA (Analysis of Variance)** – comparing means of multiple groups.

### Example

Suppose a factory produces light bulbs, and we test a **sample of 50 bulbs** to check their average lifespan:

- Sample mean lifespan: 980 hours  
- Sample standard deviation: 20 hours  
- Population unknown  

We can use a **95% confidence interval** to infer the average lifespan of all bulbs:

\[
\text{CI} = \bar{x} \pm Z \frac{s}{\sqrt{n}} = 980 \pm 1.96 \frac{20}{\sqrt{50}} \approx 980 \pm 5.5
\]

**Interpretation:** We are 95% confident that the true average lifespan of all bulbs is between **974.5 hours and 985.5 hours**.

---

**Summary Table:**

| Type of Statistics     | Purpose                                         | Key Tools & Methods                  | Example                                 |
|-----------------------|-------------------------------------------------|------------------------------------|----------------------------------------|
| Descriptive           | Summarize and describe data                    | Tables, graphs, mean, median, SD   | Exam scores summary                     |
| Inferential           | Make predictions or decisions about population | Hypothesis testing, CI, regression | Estimating average lifespan of bulbs   |
