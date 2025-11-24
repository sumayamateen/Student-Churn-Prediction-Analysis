# Student Churn Prediction Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-red)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Classification-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Models-orange)

---

## Project Overview
This project builds an **AI-powered churn prediction system** for an online learning platform to identify students at risk of dropping out.  
It combines **data cleaning, feature engineering, exploratory analysis, and machine learning modeling** to enable proactive intervention strategies.

- **Dataset:** 8,558 learner applications across 70 countries  
- **Success Rate:** 47.6% overall  
- **Churn Rate:** 31.8% of students withdraw unexpectedly
- **Tech Stack:** Python (pandas, numpy, scikit-learn, matplotlib, seaborn), Jupyter Notebook  

---

## Business Problem
- Students enroll with high motivation but many **drop out silently**  
- 31.8% withdrawal rate with no clear warning signals  
- Wasted resources and lost potential  
- Need predictive solutions for **early risk detection and churn reduction**

---

## Technical Implementation
### Data Pipeline
- Preprocessing: Handling missing values, standardizing text, mapping inconsistent values  
- Feature Engineering:  
  - Temporal: `Quick_Applicant`, `Signup_to_Apply_Days`  
  - Demographic: `Age_Group`, `Region`  
  - Behavioral: `Engagement_Score`, `Opportunity_Popularity`  
  - Composite: `Age_Major_Combo`, `Country_Gender`  

### Modeling
- Feature selection with correlation analysis to avoid data leakage  
- Algorithms tested: Logistic Regression, SVM, Random Forest, Gradient Boosting, XGBoost  
- **Final Model:** Gradient Boosting Classifier – **Accuracy: 91%**, **F1-Score: 0.86**

---

## Project Files
- `1_Data_Cleaning.ipynb` → Preprocessing & cleaning learner data  
- `2_Feature_Engineering.ipynb` → Creating engagement & derived features  
- `3_EDA_&_Data_Visualization.ipynb` → Exploring learner behavior & dropout patterns  
- `4_Predictive_Modeling.ipynb` → Building models to predict learner churn  
- `Churn_Analysis_Presentation.pdf` → Summary of workflow, insights, and recommendations  

---

## Key Insights
### Demographic Patterns
- Young adults dominate (56.7%), teens and seniors <10%  
- Gender: Male (58.4%), Female & Others  
- Geographic concentration: US and India  

### Engagement Metrics
- Average engagement score: 0.47  
- High engagement learners more likely to stay enrolled  
- Delayed first application & long courses → higher dropout risk  

### Churn Drivers
- Low regional application rates → localized disengagement  
- Chasing popular opportunities → mismatch-driven churn  

---

## Recommendations
- Personalized onboarding & early interventions  
- Restructure courses into weekly modules  
- Develop region-specific content & community hubs  
- Improve recommendation algorithm & AI-driven re-engagement prompts  

---

## Business Impact
- Shift from reactive to **data-driven interventions**  
- Reduce 31.8% churn rate through targeted strategies  
- Focus resources on **at-risk student segments**  
- Identify underserved demographics for growth opportunities  

---

**Team:** Hammad Mengrani, Kareem Mamdouh, Laiba Jawaid, Priyanka Kute, Reeba Joshi, Rifat Islam, Sumaya Mateen  

---
