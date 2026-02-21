# 📞 PwC Call Center Performance Dashboard

![Dashboard Preview](screenshots/pwc-dashboard.png)

## 📌 Project Overview

This project analyzes the PwC Call Center dataset as part of a data analytics case simulation. The objective was to evaluate customer service performance, identify operational inefficiencies, and provide actionable insights to improve overall call center effectiveness.

The dashboard delivers a comprehensive view of:

- Customer Satisfaction (CSAT)
- Call Resolution Rate
- Call Abandonment Rate
- Speed of Answer (ASA)
- Average Handling Time (AHT)
- Agent-level performance benchmarking
- Call volume trends by day and hour

This solution is designed to support data-driven decision-making for call center managers and business stakeholders.

---

## 🎯 Business Problem

PwC’s client required visibility into:

- Why customer satisfaction levels were fluctuating
- Which agents were underperforming
- When peak call volumes were occurring
- How operational KPIs were trending over time

The goal was to transform raw operational data into clear, executive-level insights.

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Description | Business Impact |
|-----|------------|----------------|
| **Total Calls** | Total inbound calls received | Measures service demand |
| **CSAT (%)** | Customer Satisfaction Score | Indicates service quality |
| **Call Resolved (%)** | % of successfully resolved calls | Measures efficiency |
| **Call Abandoned (%)** | % of dropped calls | Identifies service bottlenecks |
| **Speed of Answer (sec)** | Average time before answering | Impacts customer satisfaction |
| **Avg Handling Time (sec)** | Average duration of calls | Measures operational efficiency |

---

## 📈 Dashboard Insights

### 1️⃣ Executive KPI Summary
Provides a high-level operational health check using dynamic metric cards.

### 2️⃣ Agent Performance Analysis
Breakdown per agent including:
- Total Calls Handled
- Resolution Rate
- Abandonment %
- Speed of Answer
- CSAT

Enables identification of:
- High-performing agents
- Coaching opportunities
- Training needs

### 3️⃣ Customer Satisfaction Distribution
Calls categorized into:
- Not Served
- Very Dissatisfied
- Dissatisfied
- Normal
- Satisfied
- Very Satisfied

This highlights overall customer sentiment and service quality trends.

### 4️⃣ Call Volume by Day
Analyzes weekly call distribution to identify peak demand days and staffing optimization opportunities.

### 5️⃣ Call Volume by Hour
Intraday trend analysis (09:00–18:00) to support workforce scheduling and load balancing.

### 6️⃣ Interactive Filters
Users can dynamically filter by:
- Agent
- Topic
- Month
- Week Day

All visuals update in real time to support exploratory analysis.

---

## 🛠️ Tools & Techniques Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling & Relationship Design
- Interactive Visualizations & Slicers
- KPI Calculation & Aggregation Logic

---

## 🧠 Key Analytical Learnings

- Identified correlation between longer answer times and lower satisfaction scores.
- Observed peak call volumes early in the week, suggesting staffing realignment opportunities.
- Highlighted performance variability across agents, supporting targeted training strategies.
