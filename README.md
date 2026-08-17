# AI-Powered Collections Strategy (Tata iQ Simulation)

## 📌 Project Overview
This repository contains the deliverables from the **GenAI Powered Data Analytics** virtual job simulation by **Tata Insights and Quants (Tata iQ)**. 

The primary objective of this project was to design an AI-driven, ethical collections strategy for a simulated financial services client (Geldium Finance) to reduce credit card delinquency. The project bridges the gap between raw data analysis, predictive modeling, and strategic business decision-making.

## 🛠️ Key Skills & Tools Demonstrated
* **Exploratory Data Analysis (EDA):** Data cleaning, missing value imputation, and identifying risk indicators using Python/Pandas.
* **GenAI Prompt Engineering:** Utilizing Generative AI to scaffold predictive models and generate analytical insights without deep coding.
* **Predictive Modeling Strategy:** Designing a Logistic Regression framework prioritizing model explainability and high recall.
* **Ethical AI & Compliance:** Implementing guardrails for fairness (ECOA, GDPR) and conducting Disparate Impact analyses to prevent biased AI decisions.
* **Business Storytelling:** Translating technical model outputs into actionable, SMART business recommendations for executive stakeholders.

## 📊 Key Visualizations from EDA
During the Exploratory Data Analysis phase, several key insights were uncovered using Python. Here are some critical visualizations:

### Correlation Heatmap of Financial Indicators
This heatmap illustrates the relationships between various financial metrics, highlighting which factors most strongly correlate with delinquency.
![Correlation Heatmap](image/Correaltion%20Heatmap%20of%20Financial%20indicators.png)

### Delinquency Rate by Employment Type
This bar chart breaks down the average delinquency rate across different employment statuses, revealing key risk segments.
![Delinquency by Employment](image/Delinquency%20Rate%20by%20Employment%20Type.png)

## 📂 Repository Structure
* `Delinquency_prediction_dataset.xlsx`: The raw dataset containing customer financial behaviors, credit utilization, and repayment history.
* `Data_Exploration.ipynb`: A Jupyter Notebook demonstrating the initial exploratory data analysis, correlation checks, and visualization of key delinquency risk factors.
* `Exploratory Data Analysis.docx`: A comprehensive report outlining dataset completeness, imputation strategies (e.g., median vs. regression imputation), and preliminary anomalies.
* `Predictive Model .docx`: The conceptual architecture for a Logistic Regression predictive model, justifying the choice over "black-box" models like Neural Networks for regulatory transparency.
* `Buisness Summary Report.docx`: A strategic business proposal translating the insight that "Unemployed segments hold a ~19.3% delinquency risk" into a SMART actionable hardship-assistance campaign.
* `Geldium_AI_Collections_Strategy.pptx`: An executive-level PowerPoint deck outlining the autonomous AI system workflow, human-in-the-loop interventions, and expected business impact.
* `image/`: Directory containing the key EDA visualization charts generated from the Python notebook.

## 📈 Key Findings & Business Impact
1. **Identified Top Risk Factors:** High Credit Utilization, Debt-to-Income Ratio, and sudden Employment Instability were flagged as the strongest predictors of 30-day delinquency.
2. **Actionable Intervention:** Recommended shifting from reactive debt collection to proactive hardship assistance for high-risk segments (e.g., automated SMS deferral offers for the unemployed segment).
3. **Responsible Automation:** Designed an 'Agentic AI' loop that automates low-risk outreach while escalating high-impact interventions (like denying assistance) to human agents, ensuring strict regulatory alignment.

---
*Disclaimer: This project was completed as part of the Forage virtual experience program to simulate a real-world business environment.*