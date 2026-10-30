# Clinical Data Analysis: Heart Disease Risk Factors

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a clinical dataset of 303 patients to identify key risk factors associated with cardiovascular disease. The analysis bridges clinical medicine and data science by interpreting statistical findings through a medical lens.

## Tools Used
*   **Python** (Pandas, NumPy)
*   **Data Visualization** (Matplotlib, Seaborn)
*   **Environment** (Google Colab)

## Key Clinical Insights
*   **Overall Prevalence:** The dataset shows an overall heart disease prevalence of **54.5%**. 
*   **Gender Disparity:** Male patients demonstrated a significantly higher count of heart disease cases compared to females.
*   **Age Risk:** The distribution of heart disease is skewed toward older patients, with a peak prevalence in the 55-60 age bracket.
*   **Chest Pain Quirks:** Data revealed that 82% of patients with *Atypical Angina* had heart disease, compared to only 27% of those with *Typical Angina*. (This highlights the importance of verifying data dictionaries and noting potential cohort-specific quirks in historical datasets).
*   **Correlation Matrix:** Strong negative correlations with the target variable were observed for Exercise-Induced Angina (`exang`), ST Depression (`oldpeak`), and number of major vessels (`ca`). High max heart rate (`thalach`) showed a positive correlation with health.

## Files Included
*   `Clinical_Heart_Analysis.ipynb`: The full Python notebook containing data loading, cleaning, prevalence calculations, and visualizations.

## Author
**Overtony Sianga**
*Final-Year MBChB Candidate | Health Data Specialist*
