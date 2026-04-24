**Indian Health Insurance Claims Analysis**

# Project Overview

This project analyzes health insurance claims data to identify the key factors driving high medical costs. 
The analysis focuses on demographic, lifestyle, and treatment-related variables to uncover patterns and actionable insights.

# Objective

To answer the core business question:

**“What factors contribute to high insurance claim amounts?”**

# Tools & Technologies

**Python** (Pandas, NumPy)
**Data Visualization**: Matplotlib, Seaborn
**Notebook Environment**: Jupyter / Google Colab

# Dataset Description

The dataset contains:
**Demographics**: Age, Gender, Income, State
**Health Indicators**: BMI, Diabetes, Hypertension, Stress Level
**Lifestyle Factors**: Tobacco Usage, Alcohol Consumption
**Hospital Data**: ICU Days, Length of Stay, Hospital Tier
**Financial Data**: Claim Amount, Medical Expenses

# Data Preparation

* Cleaned mixed-format columns (e.g., currency, LPA income values)
* Handled missing values using:
 * Median imputation for numerical variables
 * “Unknown” category for categorical variables
 * Converted data types for accurate analysis

# Exploratory Data Analysis (EDA)

**Key Areas Explored:**

* Distribution of claim amounts
* Impact of ICU stays on costs
* Influence of age and BMI
* Effect of lifestyle factors (tobacco, alcohol, smoking)
* High vs low claim segmentation

# Key Insights

* **Right-Skewed Distribution**
  Claim amounts are highly skewed, with a small number of high-cost cases driving overall expenditure.

* **ICU as Primary Cost Driver**
  Patients requiring ICU care show significantly higher claim amounts, making it the strongest predictor of high costs.

* **Lifestyle Impact (Tobacco & Smoking)**
  Tobacco usage—especially combined forms—leads to higher medical expenses. Smokers also tend to incur higher claims.

* **Age Factor**
  Claim amounts increase with age, particularly for individuals above 45, with greater variability in older groups.

* **High-Risk Segments**
  High-cost claims are typically associated with a combination of:

  * ICU stays
  * Older age
  * Lifestyle risk factors

## 📈 Visualizations

The project includes:

* Distribution plots (normal vs log-transformed)
* <img width="796" height="299" alt="image" src="https://github.com/user-attachments/assets/d73d8423-896c-4fd8-961e-79d74c0ee7ef" />

* Boxplots (ICU, tobacco, alcohol, age groups)
* <img width="393" height="259" alt="image" src="https://github.com/user-attachments/assets/c139d39b-eef3-4b48-90ee-e8212e1f5db0" />

* Comparative analysis charts
<img width="1389" height="989" alt="download" src="https://github.com/user-attachments/assets/8684f7b0-4fcc-4cfe-85e0-a8856c4e7f18" />

# Business Implications

* High-cost claims are driven by **medical severity and lifestyle risks**
* Insurance providers can:

  * Improve **risk-based pricing models**
  * Focus on **preventive healthcare strategies**
  * Monitor **high-risk customer segments**

## 🚀 Conclusion

This analysis demonstrates that insurance claim amounts are not random but are strongly influenced by identifiable factors such as ICU usage, age, and lifestyle habits. 
Understanding these drivers can help insurers optimize costs and improve decision-making.

# Repository Structure

Indian-Health-Insurance/
│
├── notebook.ipynb
├── dataset.csv
├── images/
└── README.md
