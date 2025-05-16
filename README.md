# Call-Center-Performance-Report-with-Power-BI
This repository contains the essential files and documentation for a Call Center Performance Analysis project.

You can find the full project breakdown and insights on Medium here:
👉 [**The 8% Gap: How One Dashboard Revealed Hidden Call Center Failures**](https://medium.com/@UjuEmmanuella/the-8-gap-how-one-dashboard-revealed-hidden-call-center-failures-and-how-we-fixed-them-ab41c64e4e50)

---

## 🔍 Project Overview

This Power BI project analyzes over 3,000 call center records  to identify operational blind spots in the call center.
The analysis identified an 8% gap between reported issue resolution and actual customer feedback—signaling unnoticed failures affecting customer satisfaction and retention.

---

##  Problem Statement

A leading customer service center was facing:

* High call volumes but stagnant customer satisfaction scores
* Discrepancy between issue resolution data and customer feedback
* No centralized dashboard to track agent performance or resolution success
* Lack of clarity on peak issue types and escalation trends

---

## 📁 Dataset

* **Source**: Anonymised Call Center Dataset from PWC job simulation experience
* **Data**: Call logs including agent ID, call type, resolution status, duration, and customer rating
* **Sample**: 3,211 cleaned records covering multiple departments and service lines

---

## Methodology

### 1. Data Cleaning

* Checked for nulls, duplicates, and inconsistent resolution tags
* Normalized duration and satisfaction rating formats

### 2. Feature Engineering

* Created resolution accuracy metric (agent vs. customer feedback)
* Built escalation rate and peak-hour call indicators

### 3. DAX Measures

* % Resolution Accuracy
* Average Handling Time
* Customer Satisfaction Score by Agent
* Escalation Rate by Issue Category

### 4. Visualization

* KPI cards showing real-time resolution accuracy and agent performance
* Heatmap of peak call hours and issue types
* Line chart tracking satisfaction vs. resolution over time
* Interactive filters for department, agent, and issue type

---

## Key Insights

* **8% Resolution Gap**: 1 in 12 customers reported unresolved issues despite agents marking them as "resolved"
* **Escalation Hotspot**: Billing-related calls were the most difficult issues to resolve having 22% escalation rate.
* **Agent Performance**: Top 10% of agents resolved 90% of calls in under 6 minutes
* **Satisfaction Trends**: Weekday calls between 1–3 PM had the lowest satisfaction scores
* **Feedback Discrepancy**: Certain departments had consistent mismatches between internal resolution and customer feedback

---

##  Operational Highlights

* Call patterns varied significantly across departments
* Duration and satisfaction were not always positively correlated
* High-resolution rate didn't always mean higher customer happiness

---

## ✅ Recommendations

1. Investigate the 8% resolution gap – Launch a feedback audit system
2. Review billing workflows – Reduce escalations with clearer scripts
3. Reward top-performing agents – Use metrics to guide coaching and incentives
4. Optimize scheduling – Assign more agents to low-satisfaction time blocks
5. Build alert system – Flag discrepancies between resolution and feedback in real-time
6. Conduct regular data reviews – Ensure alignment between agent reporting and customer experience

---

## 📖 Full Report

👉 [Read the full Medium article here](https://medium.com/@UjuEmmanuella/the-8-gap-how-one-dashboard-revealed-hidden-call-center-failures-and-how-we-fixed-them-ab41c64e4e50)

---

## 📊 Explore the Dashboard

👉 **[View the Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTljODEyNDQtZGZjOC00ODYzLWE3NzYtMjRjZDcwZTQ1YmIyIiwidCI6IjE0ODkzNGNiLWQyMDgtNGU1Ny1hNGNkLWE2YTY2YWIyMDgwMCJ9&pageName=7c97773c71952600440a)**

---

![Performance Dashboard](Performance%20Dashboard.png)

