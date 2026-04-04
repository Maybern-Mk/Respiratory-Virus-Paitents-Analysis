# Respiratory Virus Hospital Admissions Analysis

## Overview  
This project analyzes hospital admission trends for major respiratory viruses, including COVID-19, Influenza, and RSV, over time.  

It combines exploratory data analysis, statistical hypothesis testing, and predictive modeling to understand patterns, variability, and relationships within hospital admission data.

---

## Objectives  
- Compare hospital admission patterns across respiratory viruses  
- Identify statistically significant differences between diseases  
- Analyze variability and distribution of admissions  
- Model the relationship between admission rate and new hospital admissions  

---

## Dataset Description  
- File: `Respiratory_Virus_Hospital_Admissions_Over_Time.csv`  

### Key Columns  
- `week_start_date` – Weekly time reference  
- `respiratory_virus` – Virus type (COVID-19, Influenza, RSV)  
- `new_admissions` – Number of new hospital admissions  
- `admission_rate_per_100k` – Admissions per 100,000 population  

---

## Tools and Technologies  
- **Python**  
- **Pandas**, **NumPy** for data manipulation  
- **Matplotlib**, **Seaborn** for visualization  
- **SciPy** for statistical hypothesis testing  
- **Scikit-learn** for regression modeling  

---

## Exploratory Data Analysis  

### Descriptive Statistics  
- Computed mean, median, standard deviation, quartiles, and outliers  
- Grouped statistical summaries by respiratory virus  

### Key Observations  
- Influenza shows high skewness with extreme peaks  
- COVID-19 exhibits moderate but consistent admission levels  
- RSV generally shows lower admission counts with fewer extreme values  

---

## Visual Analysis  
- Bar plots for admissions over time by virus  
- Box plots to compare distribution and variability  
- Identification of outliers and spread differences  

---

## Statistical Analysis  

### Hypothesis Testing  
- Welch’s t-tests (unequal variance):  
  - Influenza vs RSV  
  - Influenza vs COVID-19  
  - RSV vs COVID-19  

### Variance Analysis  
- F-tests used to compare variability across viruses  

### Z-Test  
- Evaluated population-level admission differences  

### Conclusions  
- Significant differences exist between admission patterns of major viruses  
- Influenza exhibits higher variance and extreme surges  
- COVID-19 shows relatively stable admission patterns compared to Influenza  

---

## Outlier Detection  
- Applied Interquartile Range (IQR) method  
- Identified unusually high admission spikes  
- Validated findings using box plot visualizations  

---

## Predictive Modeling  

### Model  
- Linear Regression  

### Features  
- `admission_rate_per_100k`  

### Target  
- `new_admissions`  

### Evaluation Metric  
- Mean Squared Error (MSE)  

### Insight  
- Admission rate per 100,000 population shows a measurable linear relationship with new hospital admissions  

---

## Project Highlights  
- Strong application of statistical analysis techniques  
- Multiple hypothesis tests with interpretation  
- Clear comparison of respiratory virus behavior  
- Integration of EDA, statistics, and machine learning  
- Use of real-world public health dataset  

---

## How to Run 
pip install pandas numpy matplotlib seaborn scipy scikit-learn

### 2. Run the Project  
- Update the dataset path if required  
- Execute the notebook sequentially  

---

## Use Case  
This analysis can support public health decision-making by identifying trends in hospital admissions, understanding disease behavior, and assisting in healthcare resource planning.

---

## Future Enhancements  
- Implement time-series forecasting (ARIMA or Prophet)  
- Apply multivariate regression including virus type as a feature  
- Perform seasonal trend decomposition  
- Build interactive dashboards using Streamlit or Power BI  
- Develop models for outbreak detection  

---

## Author  
**Mrudul Paku**  
Data Analytics | Python | Statistical Analysis | Machine Learning  


### 1. Install Dependencies  
