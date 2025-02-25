# **Lead Scoring Case Study - README**

## **Project Overview**
This project aims to improve the lead conversion rate for **X Education**, an online course provider. Currently, the company converts only **30% of leads**, and the goal is to develop a **Lead Scoring Model** that helps the sales team focus on high-potential leads, improving efficiency and boosting conversions to **80%**.

## **Project Objectives**
- **Develop a Logistic Regression Model** to predict lead conversion.
- **Assign a Lead Score (0-100)** to each lead based on probability.
- **Prioritize Hot Leads ** for focused sales efforts.
- **Provide business recommendations** to optimize marketing and sales strategies.

## **Dataset Information**
- The dataset contains **9,240 records** with lead information.
- Key features include **Lead Source, Last Activity, Total Time Spent on Website, Specialization**, etc.
- The target variable is **Converted (1 = Converted, 0 = Not Converted).**

## **Steps Followed**
1. **Data Cleaning & Preprocessing:**
   - Removed columns with excessive missing values.
   - Handled missing values using **mode/median imputation**.
   - Encoded categorical variables using **One-Hot Encoding**.

2. **Exploratory Data Analysis (EDA):**
   - Analyzed conversion trends based on **Lead Source, Last Activity, and Specialization**.
   - Identified that **Total Time Spent on Website** is a strong predictor of conversion.

3. **Model Building:**
   - Used **Logistic Regression** for classification.
   - Achieved an **Accuracy of 78%** and an **ROC-AUC score of 0.86**.
   - Generated **Lead Scores (0-100)** to rank leads by conversion probability.

4. **Business Insights & Recommendations:**
   - **Hot Leads (>70 Score)** should be prioritized for sales calls.
   - **Referrals & Welingak Website leads** convert at a higher rate.
   - **Bounced Emails** negatively impact conversion, requiring better follow-up strategies.
   
## **Key Files in This Repository**
- **`Leads.csv`** → Raw dataset containing lead information.
- **`Lead Scoring Model.ipynb`** → Jupyter Notebook with the full analysis and model implementation.
- **`Assignment Subjective Questions.docx`** → Answers to business-related questions.
- **`Lead Scoring Presentation.pdf`** → PPT summarizing findings and recommendations.
- **`Lead Scoring Summary.pdf`** → A detailed report covering the entire project.

## **How to Run This Project**
1. Clone the repository:
   git clone (https://github.com/AyushSaraswat2811/Problem_solved)
   
2. Install required dependencies:
   
   pip install -r requirements.txt
   
3. Open the Jupyter Notebook and run all cells:
   
   jupyter notebook Lead Scoring Model.ipynb


## **Future Enhancements**
- Experiment with **Decision Trees & Random Forest** for improved accuracy.
- Implement **Automated Lead Categorization** with AI-driven recommendations.
- Develop a **Web Dashboard** to visualize lead scores in real-time.

---
