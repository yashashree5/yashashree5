<div align="center">

# Yashashree Shinde

**Software Engineer → Data Engineer & Data Scientist**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashashree1/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/yashashree5)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:yashashree.shinde@sjsu.edu)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=flat-square&logo=google-drive&logoColor=white)](https://raw.githubusercontent.com/yashashree5/yashashree5/main/Yashashree_Resume_DE.pdf)

</div>

---

## The Story So Far

I spent two years at Barclays watching what happens when data pipelines fail at scale.

My team's system processed **100,000+ financial transactions every single day.** Every morning before markets opened, Risk, Finance, and Treasury teams were waiting on reports that my pipelines produced. There was no "approximately right." The numbers had to be correct, reconciled, and delivered on time — every single day.

That experience gave me something most data science grads don't have: **a deep respect for what happens between raw data and a trusted insight.** I've felt the pressure of a reconciliation check catching an error before it hits a risk report. I've optimized SQL pipelines not for elegance, but because a 20% speed improvement meant faster decisions for senior stakeholders. I've built data quality frameworks because downstream discrepancies have real consequences.

But after two years of building systems that told people *what happened*, I kept asking the harder question: **what if we could predict what's about to happen?**

That question brought me to SJSU's MS in Applied Data Intelligence — and to building every project you'll see below.

---

## What I'm Building

I work across three areas that I think belong together:

**Data Engineering** — pipelines that are reliable, observable, and production-ready. Airflow, dbt, Snowflake, Spark. Not just notebooks.

**Data Science & ML** — models that answer real business questions. Fraud detection, churn prediction, credit risk scoring. Built to be interpretable and actionable, not just accurate.

**Risk & Business Analytics** — the translation layer. Turning model outputs and pipeline data into decisions that stakeholders can actually use. This is where my Barclays years live.

---

## Projects (and Why I Built Them)

### 🚨 [IncidentIQ – AI-Powered Incident Management](https://github.com/yashashree5/IncidentIQ)
`PostgreSQL · Airflow · dbt · Streamlit · Docker · OpenAI API`

After years of being on-call for production systems, I understood the real cost of slow incident response — not in theory, but in late nights and escalation chains. I built IncidentIQ to automate the triage work I used to do manually.

- End-to-end pipeline: PostgreSQL → dbt transformations → Airflow orchestration → Streamlit dashboard
- AI-generated incident summaries and remediation suggestions via OpenAI API
- Near real-time SLA tracking with automated alerting
- Reduced simulated resolution time by **70%**

*What I learned: orchestration is everything. A great model inside a broken pipeline is worthless.*

---

### 📊 [Loan Default Risk Analysis](https://github.com/yashashree5/loan-default-risk-analysis)
`Python · SQL · XGBoost · Scikit-learn · A/B Testing`

I wanted to approach credit risk the way a data scientist at a bank actually would — not just build a model, but produce something a risk officer could act on.

- Analyzed **255,347 loan records**, built 3 ML models with threshold optimization for high-risk recall
- Ran a proper A/B test: co-signers reduce default rates by **19.5%** (p < 0.0001)
- Built a 4-tier risk scorecard — highest tier defaults at **9× the rate** of the lowest
- Finding: unemployed borrowers are **24% more likely to default**, 14.4% of all loans default before maturity

*What I learned: the model is 20% of the work. The other 80% is understanding what the business will do with the output.*

---

### 📉 [Telco Customer Churn Analysis](https://github.com/yashashree5/telco-churn-analysis)
`Python · SQL · Scikit-learn · Tableau`

Churn is a revenue problem before it's a data problem. I wanted to find where the money was leaking — and be specific enough that a retention team could act on it immediately.

- Churn prediction model: **AUC 0.81**
- SQL cohort analysis: churn doesn't stabilize until **month 19** — an onboarding problem, not a product problem
- Traced **$819K in annual revenue loss** to a single customer segment
- Month-to-month customers churn at **42%** vs. 3% for two-year contracts

*What I learned: the most valuable insight isn't the model's accuracy. It's the one number that changes what the business does on Monday.*

---

### 💳 [Credit Fraud Detection](https://github.com/yashashree5/Credit_Fraud_Detection_System)
`Python · LightGBM · Streamlit`

Fraud detection is a class imbalance problem first, an ML problem second. I wanted to work through that tension directly rather than ignore it.

- LightGBM classifier with explicit class imbalance handling
- Real-time transaction scoring with live Streamlit dashboard
- Built for interpretability — flagged transactions show contributing features

*What I learned: in high-stakes predictions, false positives aren't just noise — they're customer trust. Every threshold decision is a business decision.*

---

### 🚇 [BART Transit Intelligence](https://github.com/yashashree5/BART-Transit-Intelligence)
`Python · Spark · Snowflake · Streamlit · Plotly`

My first fully streaming project. I wanted to experience the complete lifecycle of real-time data — from live ingestion through transformation to an interactive dashboard — using infrastructure that could actually scale.

- Spark streaming pipeline for live BART transit data
- Snowflake for efficient storage and query optimization
- Interactive Streamlit + Plotly dashboard with live updates

*What I learned: real-time data is a different mental model. Latency isn't a bug — it's a design constraint.*

---

### 🍳 [SnowChef – Smart Pantry & Recipe Warehouse](https://github.com/yashashree5/Snowchef)
`Snowflake · Airflow · dbt · Snowpark ML · Tableau`

An excuse to learn Snowpark ML end-to-end while solving a problem I actually have: standing in a kitchen with ingredients and no plan.

- Full Snowflake data warehouse with recipe APIs + synthetic datasets
- Snowpark ML for personalized recipe recommendations
- Airflow + dbt for pipeline orchestration and transformations
- Tableau dashboards for ingredient trends and recipe popularity

*What I learned: recommendation systems are deceptively hard to evaluate. "Did the user cook it?" is a much better metric than model loss.*

---

## Background

**Software Engineer (BA4) · Barclays Investment Bank** *(Jul 2023 – Aug 2025, Pune)*
Production risk & data analytics — trade booking platform processing 100K+ daily transactions, SQL pipeline optimization, data quality frameworks, SOX audit support

**M.S. Applied Data Intelligence · San José State University** *(Aug 2025 – May 2027)*
Machine Learning · Data Warehousing & Pipelines · Data Visualization

**B.E. Computer Engineering · Savitribai Phule Pune University** *(2019 – 2023)* · GPA 3.5

---

## Tech Stack

| Area | Tools |
|------|-------|
| **Languages** | Python · SQL · Java |
| **Data Engineering** | Apache Airflow · dbt · Apache Spark · Snowflake · PostgreSQL · MySQL · MongoDB |
| **ML & Analytics** | Scikit-learn · XGBoost · LightGBM · Snowpark ML · A/B Testing · Statistical Modeling |
| **Cloud & DevOps** | AWS · Docker · Git |
| **Visualization** | Tableau · Power BI · Streamlit · Plotly · Matplotlib · Seaborn |

---

<div align="center">

*"I came for the engineering. I stayed for the question: what does the data actually mean?"*

📍 San Jose, CA &nbsp;·&nbsp; [yashashree.shinde@sjsu.edu](mailto:yashashree.shinde@sjsu.edu)

</div>
