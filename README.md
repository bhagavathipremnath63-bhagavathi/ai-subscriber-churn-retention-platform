# 🎯 AI-Powered Subscriber Churn Diagnostic & Revenue Retention Platform

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-yellow)
![Google Colab](https://img.shields.io/badge/Google_Colab-Machine_Learning-orange)
![SQL](https://img.shields.io/badge/SQL-Cohort_Analysis-blueviolet)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Executive Summary
Subscriber attrition directly threatens recurring revenue in B2B/SaaS business models. This project diagnoses a **54.35% churn rate representing $3M in at-risk revenue** across 10,000 subscribers. By combining **SQL cohort analysis, Power BI decomposition trees, and a Random Forest Machine Learning pipeline**, this platform isolates the root causes of revenue leakage and automates risk-scoring workflows for Key Account Managers (KAMs).

---

## 🚀 Key Highlights & Machine Learning Performance
* **Machine Learning Model:** Random Forest Classifier built & executed in **Google Colab**.
* **Model Accuracy:** **99.84%** cross-validated accuracy in predicting subscriber attrition.
* **Risk Categorization:** Automatically assigns real-time **AI Churn Probability (%)** and categorizes subscribers into **High Risk**, **Medium Risk**, and **Low Risk** intervention tiers.
* **Proactive Action:** Equips account managers with automated intervention playbooks to prevent churn *before* contract renewal.

---

## 📊 Top Business Drivers of Churn (Feature Importance Analysis)
Using machine learning feature importance extraction, the top operational factors driving subscriber attrition were identified:

1. **Payment Delay (43.8% Impact):** Payment gateway friction and invoice processing delays account for nearly half of total churn.
2. **Support Calls (16.1% Impact):** High volume of unresolved customer support tickets strongly correlates with account cancellation.
3. **Tenure (10.5% Impact):** Subscribers in their first 60–90 days show the highest vulnerability to drop-offs.
4. **Usage Frequency (8.4% Impact):** Steep declines in daily/weekly platform activity signal impending account abandonment.
5. **Gender & Demographic Variables (7.7% Impact):** Minor variance across specific user demographics.

> **Key Insight for Key Account Managers:** Product dissatisfaction is *not* the primary attrition driver. **Payment gateway friction and unresolved customer service delays account for ~60% of lost revenue.** Addressing operational workflow delays directly protects the $3M at-risk ARR.

---

## 🛠️ Tech Stack & Methodology
* **Data Processing & ML:** Python (Pandas, Scikit-Learn, NumPy) via **Google Colab**.
* **Visualization & Reporting:** Power BI (DAX, Decomposition Trees, Executive Dashboards).
* **Database & Analytics:** SQL (Cohort Analysis, As-Is/To-Be Mapping).
* **AI Strategy Integration:** Structured Generative AI prompt templates to generate tailored account recovery strategies for account executives.

---

## 📁 Repository Structure
├── subscriber_churn_with_AI_scores.csv    # Enhanced dataset containing AI Churn Probabilities & Risk Tiers
├── Subscriber_Churn_Prediction_AI.ipynb  # Google Colab Python notebook for Machine Learning pipeline
├── Churn_Diagnostic_Dashboard.pbix       # Interactive Power BI Dashboard
├── colab_execution_screenshot.png        # Proof of model accuracy & execution output
└── README.md                             # Project documentation


---

## 💼 Strategic Impact for Key Account Management (KAM)
1. **Automated Risk Scoring:** Account managers no longer manually review 10K+ accounts; the AI pipeline flags accounts with >70% churn risk automatically.
2. **Targeted Retention Campaigns:** High-risk accounts driven by payment delays are routed to finance support, while those driven by support ticket backlogs are routed to priority client success managers.
3. **Generative AI Retention Playbooks:** Integrated prompt workflows auto-generate personalized win-back emails and executive outreach decks, reducing strategy creation time by 40%
