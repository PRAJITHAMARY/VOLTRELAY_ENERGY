
# ⚡ VoltRelay Energy — Battery Swap Network Analytics

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white">

<img src="https://img.shields.io/badge/Pandas-Data%20Analytics-150458?style=for-the-badge&logo=pandas&logoColor=white">

<img src="https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">

<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge">

</p>
<p align="center">
  <b>Data-Driven Intelligence for Battery Swapping Networks</b>
</p>

<p align="center">
  Turning millions of battery-swap events into actionable insights for operations, reliability, profitability, and customer retention.
</p>

---

## 📌 Project Overview

VoltRelay Energy is a data analytics project developed as part of the **Data Analytics Hackathon conducted by Gradient**.

The project analyzes a large-scale synthetic battery-swapping dataset containing millions of swap events across major Indian cities.

The objective is to understand:

- Why battery swaps fail
- Which stations experience higher failure rates
- How queue waiting time affects swap success
- How battery health influences failures
- Which vehicle classes are more affected
- How fleet partners perform
- How pricing affects revenue and margins
- What factors influence rider retention

The project combines **Exploratory Data Analysis, Business Intelligence, Predictive Analytics, and Machine Learning** to convert raw operational data into meaningful business decisions.

---

## 🎯 Business Problem

Battery-swapping networks operate across multiple stations, cities, vehicle types, riders, batteries, and fleet partners.

With millions of swap attempts, identifying the root causes of service failures becomes difficult using traditional reporting.

VoltRelay aims to answer:

> **"What is causing swap failures, where are they happening, and what actions can improve reliability and profitability?"**

---

## 📊 Dataset

The analysis uses a synthetic battery-swapping network dataset representing VoltRelay Energy operations from **January 2024 to June 2025**.

### Dataset Scale

| Dataset | Records |
|---|---:|
| Swap Events | ~3.9 Million |
| Riders | 20,000 |
| Batteries | 6,500 |
| Stations | 152 |
| Support Tickets | 44,000 |
| Fleet Partners | 12 |
| Daily City Context | 3,282 |

### Major Cities

- Bengaluru
- Delhi NCR
- Hyderabad
- Pune
- Mumbai
- Jaipur

---

# 🔍 Key Business Questions

The project focuses on six major analytical areas.

### 1. Operational Reliability

Which stations, cities, time periods, and operating conditions experience the highest swap failure rates?

### 2. Queue & Service Performance

How does queue waiting time influence swap failures and rider abandonment?

### 3. Battery Health

Does battery State of Health (SOH) contribute to swap failures?

### 4. Fleet Partner Performance

Which fleet partners experience higher failure rates and operational issues?

### 5. Revenue & Profitability

How do tariff types, pricing, discounts, and energy costs affect revenue and gross margin?

### 6. Rider Retention

Which onboarding channels and rider characteristics are associated with repeat usage?

---

# 🧠 Analytics Workflow

```text
                    RAW DATA
                       │
                       ▼
              Data Understanding
                       │
                       ▼
              Data Cleaning
                       │
                       ▼
             Data Transformation
                       │
                       ▼
          Exploratory Data Analysis
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
      Operations    Finance      Customer
          │            │            │
          ▼            ▼            ▼
      Reliability   Profitability  Retention
          │            │            │
          └────────────┼────────────┘
                       ▼
              Predictive Analytics
                       │
                       ▼
              Business Insights
                       │
                       ▼
                DASHBOARD
                       │
                       ▼
              BUSINESS ACTIONS
