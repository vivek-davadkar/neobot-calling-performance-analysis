# 📞 NeoBot Calling Performance Analysis

## Overview

This project analyzes call and payment interaction data from **NeoBot**, a conversational AI agent, based on its performance on **May 11th**. The goal is to evaluate key metrics such as pickup rates, payment behavior, and promise-to-pay (PTP) follow-through, and generate actionable insights to improve bot efficiency and customer engagement.

---

## Objectives

- Analyze overall calling and connection efficiency
- Evaluate borrower payment behavior post-call
- Identify successful PTP conversion rates
- Visualize key distributions such as call durations and calls per borrower
- Extract top insights to inform product and strategy decisions

---

## Key Metrics Extracted

- **Borrowers Called**  
- **Borrowers Connected / Pickup Rate**  
- **Unique Pickups and Rates**  
- **Total Calls Made**  
- **PTP Count and PTP Rate**  
- **Payment Behavior** (Paid Borrowers, Called + Paid, Pickup + Paid)  
- **PTP Conversion Rate**  
- **Call Volume Metrics** (Max Calls, Avg Calls)  
- **Call Duration Distribution**

---

## Technologies Used

- **Python**
- **Pandas**  
- **Matplotlib & Seaborn** for visualizations  
- **Jupyter Notebook**

---

## Output

- Tabular summaries
- Donut and pie charts for percentage metrics
- Histograms and lollipop charts for distributions
- Business insights based on data trends

---

## Top Insights (Examples)

- High PTP conversion among borrowers who picked up
- Majority of payments came from borrowers who were both called and connected
- Short-duration calls make up a significant portion of total interactions
- Few borrowers required many follow-ups, indicating opportunity for smarter retry logic
- Certain call dispositions underperform or show anomalies worth deeper investigation

---

## Getting Started

1. Clone the repository  
```bash
git clone https://github.com/vivek-davadkar/neobot-calling-performance-analysis.git

