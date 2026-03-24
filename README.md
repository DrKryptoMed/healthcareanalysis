# Exploratory Data Analysis: COVID-19 Clinical Trials

## 📊 Project Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) of **5,783** COVID-19 clinical trials. This project maps the global scientific response to the pandemic through the lens of public health, research rigor, and demographic inclusivity.

## 🎯 Research Objectives
1. **Temporal Dynamics:** Analyze status distribution and trial duration.
2. **Demographic Inclusivity:** Assess eligibility across age groups and genders.
3. **Scientific Profiling:** Profile intervention types and clinical phases.
4. **Operational Scale:** Evaluate enrollment scale and study design rigor.
5. **Funding Landscape:** Identify major research sponsors and sectors.

## 🛠️ Data Engineering & Validation
* **Missingness Management:** Classified data as **MCAR** (e.g., Enrollment) or **MAR** (e.g., Phases).
* **Feature Engineering:** Used **Regex** to extract age groups (Child, Adult, Older Adult) and unpacked complex "Study Design" strings into granular columns for **Allocation** and **Masking**.
* **Time-Series Prep:** Converted multiple date columns into `datetime` objects for duration analysis.

## 📈 Key Insights
* **Rapid Tempo:** The median duration for a COVID-19 trial was **298 days**.
* **Inclusivity Gap:** While gender inclusivity was high, only **5.5%** of trials were fully inclusive across all age brackets.
* **Academic-Driven:** The funding landscape was dominated by **Hospitals and Universities** (4,471 trials) over private **Industry** (629 trials).
* **Top Sponsor:** **Assistance Publique - Hôpitaux de Paris** led the global effort with 78 trials.

## 📂 Repository Structure
* `Covid_Trial_Analysis.ipynb`: Main Python analysis notebook.
* `Covid_clinical_trial_analysis.pdf`: Detailed scientific report.
* `README.md`: Project documentation.

---
**Note:** This project is part of my roadmap in **Healthcare Data Science** and **AI** with special application in  **Computational and Precision Oncology**.
