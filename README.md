# Predicting Well-being Disparities Across Socio-Economic Groups and in Relation to Climate and Environmental Risk

**Group Members:**  
Armande Aboudrar-Méda, Henry Baker, Giorgio Coppola, Lino Hans Julian Zurmuehl

---

## 📖 Project Overview

**Title:** Predicting Well-being Disparities Across Socio-Economic Groups and in Relation to Climate and Environmental Risk

This project aims to build a multi-class classification model that predicts self-perceived health status (`sphus`, five levels) for EU residents aged 50+, using socioeconomic, health, demographic, and environmental features.

---

## 🔍 Theoretical Mechanism

Individuals from lower socioeconomic status (SES) backgrounds often live and work in areas with poorer environmental conditions—higher pollution, inadequate housing, and limited access to clean water and air—due to historical, economic, and social factors. Exposure to environmental hazards (e.g., air pollution, extreme temperatures) compounds other SES vulnerabilities (limited healthcare access, poor nutrition, economic stress), leading to higher rates of respiratory, cardiovascular, and stress-related illnesses.

---

## 🧮 Units of Analysis

- **Each row** in the dataset represents one individual respondent: an EU resident aged 50+.

---

## 🎯 Prediction Target

- **Label:** Self-perceived health status (`sphus`), a categorical variable with five levels.  
- **Problem Type:** Multi-class classification.

---

## 🛠 Features

### Health Variables
- Presence of chronic diseases (e.g., heart disease, diabetes, respiratory diseases)  
- Mental health indicators (e.g., depression scores)  
- Illness and health conditions related to environmental exposure (`Ill_any_env_related_issue` [1/2/3]):  
  - Angina or heart attack  
  - Stroke  
  - Asthma  
  - Other respiratory problems  
  - Migraines  
  - Emotional distress  
  - Fatigue  
  - Infectious diseases  
  - Allergies  

### Environmental Exposure Variables
- Regional pollutant concentrations (e.g., PM2.5, NO₂)  
- Exposure to extreme temperatures and radiation  
- Cumulative environmental hazard indices  
- Food event data  

### Socio-Economic Variables
- Household net worth  
- Household income (current and average)  
- Education level (ISCED classification)  
- Housing quality  
- Location of dwelling (city, suburb, town, rural)  
- Work conditions  

### Demographic Variables
- Age, gender, and other standard demographics  

---

## 🤔 Decision-Making Context

Predictions can inform public health and environmental justice policies by:

- **Identifying vulnerable groups** most at risk from poor environmental quality  
- **Guiding targeted interventions** and resource allocation  
- **Advocating for improved environmental conditions** in disadvantaged areas  
- **Shaping strategies** to mitigate environmental health impacts among older adults  

---

## ⚙️ Model Selection

To understand the impact of environmental factors on well-being inequalities:

1. **Baseline Model (SES + Health + Demographics):** Captures relationships between socioeconomic factors, health behaviors, and outcomes.  
2. **Full Model (Baseline + Environmental Variables):** Adds pollution levels, temperature extremes, and hazard indices to gauge improvement in predictive accuracy.  

By comparing both models, we can quantify the added value of environmental features and support evidence-based policy recommendations that incorporate environmental risk reduction into efforts to close health-inequality gaps.

---

*This repository contains all data preprocessing scripts, exploratory analyses, model implementations, and evaluation results corresponding to the above project plan.*
