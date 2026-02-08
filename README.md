🫁 Respiratory Virus Hospital Admissions Analysis

This project analyzes hospital admission trends for major respiratory viruses—COVID-19, Influenza, and RSV—over time.
It combines exploratory data analysis, statistical hypothesis testing, and predictive modeling to understand patterns, variability, and relationships within the data.

🎯 Objective

Compare hospital admission patterns across respiratory viruses

Identify statistical differences between diseases

Analyze variability and distribution of admissions

Model the relationship between admission rate and new hospital admissions

📂 Dataset Description

Respiratory_Virus_Hospital_Admissions_Over_Time.csv

Key columns:

week_start_date – Weekly time reference

respiratory_virus – Virus type (COVID-19, Influenza, RSV)

new_admissions – Number of new hospital admissions

admission_rate_per_100k – Admissions per 100,000 population

🛠️ Tools & Libraries Used

Python

Pandas, NumPy – data manipulation

Matplotlib, Seaborn – data visualization

SciPy – statistical hypothesis testing

Scikit-learn – regression modeling

🔍 Exploratory Data Analysis (EDA)
Descriptive Statistics

Computed mean, median, standard deviation, quartiles, and outliers

Grouped statistics by respiratory virus

Key Observations

Influenza shows high skewness with extreme peaks

COVID-19 has moderate but consistent admission levels

RSV generally exhibits lower admission counts with fewer extremes

📊 Visual Analysis

Bar plots: Admissions over time by virus

Box plots: Distribution and variability across viruses

Identified outliers and spread differences visually

📈 Statistical Analysis
Hypothesis Testing

Welch’s T-tests (unequal variance):

Influenza vs RSV

Influenza vs COVID-19

RSV vs COVID-19

Variance Analysis

F-tests used to compare variability between viruses

Z-Test

Tested population-level admission differences

Conclusions

Significant differences exist between admission patterns of major viruses

Influenza shows higher variance and extreme surges compared to RSV

COVID-19 admissions remain more stable relative to Influenza

📉 Outlier Detection

Used Interquartile Range (IQR) method

Identified unusually high admission spikes

Supported findings from box-plot visualizations

🤖 Predictive Modeling
Model Used

Linear Regression

Features

admission_rate_per_100k

Target

new_admissions

Evaluation Metric

Mean Squared Error (MSE)

Insight

Admission rate per 100k population shows a measurable linear relationship with new hospital admissions

📌 Project Highlights

✔ Strong use of statistical reasoning
✔ Multiple hypothesis tests with interpretation
✔ Clear comparison of virus behavior
✔ Combination of EDA + stats + ML
✔ Real-world public health dataset

🚀 How to Run

Install dependencies:

pip install pandas numpy matplotlib seaborn scipy scikit-learn


Update dataset path if required

Run the notebook sequentially

🔮 Possible Extensions

Time-series forecasting (ARIMA / Prophet)

Multivariate regression with virus type as a feature

Seasonal trend decomposition

Public health dashboard (Streamlit / Power BI)

Logistic modeling for outbreak detection

cs portfolio

Just say the word 👌
