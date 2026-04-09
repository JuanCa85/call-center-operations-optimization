# 📞 Call Center Operations Optimization

Analyzed call center operations to identify inefficiencies, optimize resource allocation, and improve service performance by leveraging KPI-driven insights.

---

## ⚡ TL;DR

- Identified underperforming operators using KPI analysis  
- Detected inefficiencies in workload distribution and missed call rates  
- Delivered actionable recommendations to improve operational efficiency and service quality   

---

## 🚀 Business Problem

Call centers rely heavily on operational efficiency to maintain service quality and control costs.

The company needed to identify underperforming operators and understand the root causes of inefficiencies impacting performance.

---

## 📌 Project Type

Business-focused data analysis project aimed at improving operational efficiency.

---

## 🎯 Objective

- Detect inefficient operators based on performance metrics  
- Identify key factors affecting productivity  
- Provide actionable insights to improve operational efficiency  

---

## 💡 Key Takeaway

Operational inefficiencies are driven not only by individual performance but also by workload imbalance and process inefficiencies.

---

## 🧠 Approach

1. Data Cleaning & Preparation  
   - Processed call logs and performance metrics  
   - Handled missing and inconsistent data  

2. Exploratory Data Analysis  
   - Analyzed call duration, wait times, and operator activity  
   - Evaluated performance distribution across operators  

3. KPI Analysis  
   - Defined key metrics (e.g., handling time, call volume, efficiency)  
   - Compared operator performance against benchmarks  

4. Insight Generation  
   - Identified patterns of inefficiency  
   - Detected outliers and performance gaps  

---

## 📈 Key Insights

- **39% of inbound calls and 47% of outbound calls are missed** — significantly above industry benchmarks
- **Inefficient operators lose 1 in 2 calls** — missed call rate averages **50.3%** vs **22.1%** for the rest of the team
- **Wait time is the clearest differentiator** — inefficient operators average **876 seconds (14.6 min)** of hold time; the worst case reached **5,325 seconds (88 minutes)**
- **The problem is skill-based, not workload-based** — correlation between call volume and missed rate is only -0.121, meaning operators with more calls don't perform worse
- **8,172 calls (15.2%) were never assigned to any operator**, concentrated on Monday, Thursday, and Sunday at 21:00 — a systemic staffing gap, not an operator issue 

---

🏆 Results

- ✅ Classified **713 operators** after filtering for minimum activity (≥10 calls, ≥3 active days)
- ✅ Identified **159 operators with call management issues** (high missed rate + high hold time)
- ✅ Confirmed findings with **ANOVA statistical testing** — differences are significant at p < 0.001 for missed call rate and hold time
- ✅ Separated operator-level problems from systemic infrastructure gaps

---

## 💡 Key Takeaway

Operational inefficiencies are driven not only by individual performance but also by workload distribution and process-related factors.

---

## 🧩 Recommendations

- **Immediate: Cover the 21:00 gap on Mon/Thu/Sun** — 52% of all calls hit during this window with insufficient operator coverage; adding shifts or on-call coverage would have the highest ROI
- **Uptraining for 159 flagged operators** — focus on call handling techniques, system efficiency, and managing difficult calls; the problem is consistent across all volume levels, confirming it's skill-based
- **Fix the unassigned call routing** — 8,172 calls reached no operator; implement auto-routing or overflow protocols to capture this volume
- **Track post-training performance** — re-evaluate the 35 low-activity operators excluded from this analysis after 60 days to assess if inefficiency persists past the learning curve

---

## 💼 Business Impact

This analysis enables organizations to:

- Improve operational efficiency  
- Enhance service quality  
- Optimize resource allocation  
- Reduce operational costs  

This analysis enables a shift from reactive to proactive operations management.

---

## 📊 Visual Insights

### Operator Performance Distribution
![Operator Performance](https://github.com/JC-Insights/call-center-operations-optimization/blob/main/images/operator_performance.png)

Significant variability in call volume across operators suggests uneven workload distribution.

### Call Handling Time Analysis
![Call Duration](https://github.com/JC-Insights/call-center-operations-optimization/blob/main/images/call_duration.png)

### Call Volume Analysis
![Call Volume](https://github.com/JC-Insights/call-center-operations-optimization/blob/main/images/missed_vs_calls.png)

### KPI Comparison
![KPI Analysis](https://github.com/JC-Insights/call-center-operations-optimization/blob/main/images/kpi_analysis.png)

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)  
- Data Visualization (Matplotlib, Seaborn)  
- Exploratory Data Analysis  
- KPI Analysis  

---

## 📁 Project Structure

call-center-operations-optimization/
│  
├── data/  
├── notebooks/  
├── images/  
└── README.md  

---

## 📌 Author

Juan Carlos Vértiz Millán  
Data Analyst | Python • SQL • Power BI
