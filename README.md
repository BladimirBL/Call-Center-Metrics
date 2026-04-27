# 📞 Call Center Metrics — Operational Performance Analysis

> Data analysis project focused on identifying operational patterns in a call center by analyzing call volume, staffing levels, efficiency, and abandoned call rates across different shifts. The goal is to uncover peak demand periods and propose data-driven staffing and resource optimization strategies.

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bladimir-andres-hernandez-a1764a2b7)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bladimir4hernandez@gmail.com)

---

## 📌 Project Overview

A call center operation generates a constant stream of performance data across multiple shifts and days. This project analyzes that data to understand how call volume, operator availability, efficiency, and abandoned calls vary by time period — and what that means for operational planning.

The analysis covers three daily shifts **(7AM–3PM, 3PM–11PM, 11PM–7AM)** across both weekdays and weekends, providing a comprehensive view of when the operation is under pressure and where improvements can be made.

---

## 🎯 Key Questions Answered

- Which shift handles the highest call volume on average?
- When are abandoned calls most frequent — and why?
- How does operator staffing correlate with efficiency and utilization rates?
- Are there meaningful differences in performance between weekday and weekend shifts?
- What average wait times are customers experiencing across each shift?

---

## 🔍 Methodology

```
1. Data Cleaning & Preprocessing
   - Parsing and splitting date ranges (Start_Date / End_Date)
   - Standardizing column names for all 21 metrics
   - Removing null values and verifying no duplicates

2. Exploratory Data Analysis (EDA)
   - Average call volume per shift
   - Average abandoned calls per shift
   - Bar chart visualization of call volume distribution across shifts

3. Operational Metrics Analysis
   - Efficiency rates by time period
   - Utilization rates by time period
   - Average wait times (seconds) by shift
   - Operator headcount comparison: Mon–Fri vs. Sat–Sun
```

---

## 📊 Key Findings & Conclusions

### 📈 Call Volume Patterns
- The **morning shift (7AM–3PM)** consistently handles the largest share of daily call volume, making it the most operationally critical period.
- The **overnight shift (11PM–7AM)** has significantly lower volume, though efficiency and staffing ratios remain relevant for service quality.

### 🚨 Abandoned Calls
- Abandoned call rates are highest during **peak-volume shifts**, suggesting that staffing levels don't always scale proportionally with demand.
- Reducing abandonment during the morning and afternoon shifts is the clearest opportunity to improve customer experience.

### ⚙️ Efficiency & Utilization
- Efficiency and utilization metrics vary across shifts, highlighting periods where operators may be over- or under-utilized.
- Aligning staffing levels more closely with call volume patterns could improve both metrics simultaneously.

### ⏱️ Wait Times
- Average wait times (in seconds) differ across shifts and reflect the combined effect of call volume, staffing, and handling efficiency.
- Shifts with high volume and lower operator counts show the longest wait times.

### 💡 Operational Recommendations
1. **Reinforce morning shift staffing** — The 7AM–3PM window drives the most volume; ensure adequate coverage to reduce abandonment and wait times.
2. **Review weekend staffing ratios** — Weekend shifts may be understaffed relative to actual call demand.
3. **Monitor overnight efficiency** — Low volume doesn't mean low importance; overnight service quality affects customer satisfaction.
4. **Set abandonment rate targets** — Use historical averages as benchmarks and trigger alerts when rates exceed acceptable thresholds.

---

## 📁 Project Structure

```
📦 call-center-metrics-analysis
 ┣ 📓 Call_center_metrics.ipynb   # Main analysis notebook
 ┣ 📄 Call_center_metrics.csv     # Source dataset
 ┗ 📄 README.md
```

---

⭐ *If you found this project useful, feel free to leave a star!*
