# 🚲 YULU Ride Duration Analysis - Hypothesis Testing Project

This project investigates whether the average ride durations on weekdays are significantly different from those on weekends for the micro-mobility startup YULU. Using statistical hypothesis testing, the analysis supports data-driven decision-making regarding pricing or operational strategy.

---

## 🎯 Objective

To perform a two-sample hypothesis test (t-test) to check:
> "Are ride durations on weekdays higher than those on weekends?"

---

## 📈 Approach

1. **Data Cleaning**:
   - Removed missing values
   - Filtered extreme outliers in duration

2. **Exploratory Data Analysis**:
   - Created histograms, boxplots, and summary statistics
   - Compared distribution of ride durations between weekdays and weekends

3. **Hypothesis Testing**:
   - Formulated H₀ and H₁
   - Applied two-sample t-test using `scipy.stats`
   - Interpreted p-value and decision rules

---

## 🧠 Key Insight

- Result showed that average weekday ride durations are **not significantly higher** than weekends at 95% confidence level
- Business implication: no immediate need for pricing adjustment based on duration patterns

---

## 📁 File Included

- `YULU_Project_Hypothesis_Testing.ipynb`: Google colab notebook with full EDA and test

---

## 🛠 Tools Used

- Python
- pandas, matplotlib, seaborn
- scipy.stats (t-test)

---

## 👤 Author

**Popatsing Waghela**  
Data Analyst (Finance Background)  \  
[LinkedIn](https://www.linkedin.com/in/popatsing-waghela-3b7a87246) | [GitHub](https://github.com/Waghela007)

---

_This project showcases real-world application of statistics and hypothesis testing using Python for business insights._
