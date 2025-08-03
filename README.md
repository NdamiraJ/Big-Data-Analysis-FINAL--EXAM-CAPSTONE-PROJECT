## 📊 Youth Employment in Rwanda — Analytics & Visualization Project

🔍 Problem Statement

How can we identify and visualize patterns in youth employment across Rwanda using national survey data? 

This project explores demographic disparities, education-employment links, and economic sectors absorbing youth labor based on EICV7 datasets.

🚀  PYTHON ANALYTICS TASKS

1. 🧼 Data Cleaning

Handled missing values using conditional imputation and row exclusion

Normalized column formats (capitalization, whitespace)

Converted percentage strings to numeric floats

Applied StandardScaler for feature scaling

2. 📊 Exploratory Data Analysis (EDA)

Generated descriptive statistics (describe())

Visualized distributions using histograms, boxplots, and bar charts

Explored relationships between school attendance, occupation, and wage employment by gender

3. 🧠 Clustering Model

Applied KMeans clustering on standardized features:

% Technical/Vocational School Attendance (EICV5 & EICV7)

Occupation Group

Sector

Wage_Male, Wage_Female

Clustered occupation-sector combinations into employment behavior groups

4. 📈 Model Evaluation

Used Silhouette Score to assess cluster cohesion and separation



5. 🧩 Modular Code Structure

Organized reusable functions for loading, cleaning, clustering, and evaluating

Included markdown cells for step-by-step explanations




📊  POWER BI DASHBOARD TASKS

1. 🧠 Insight Communication
Included summary cards for overall youth employment rates.


2. 🎛️ Interactive Features
Added slicers for:

Sector

Occupation Group

Gender

Cluster Type



3. 📈 Appropriate Visuals

Cluster-wise bar charts for attendance and wage gaps

Heat maps for school attendance rates by occupation

Line charts showing change between EICV5 and EICV7

Tools & Environment Setup

Required Software:

- Python (v3.8+ recommended) https://www.python.org/downloads/ 

- VS Code or Jupyter Notebook https://code.visualstudio.com/download 

- Power BI Desktop https://www.microsoft.com/en-us/download/details.aspx?id=58494

Dataset Identification 

-	Dataset title: Youth_Thematic_Report_EICV7 and EICV7_Tables_Youth_Thematic_Report
-	Source Link: https://www.statistics.gov.rw/statistical-publications/gender-and-youth/youth
-	Data Structure: Unstructured

Power BI Dashboard
Click here to access it https://drive.google.com/file/d/1WAT26O9tY2eSaCM6VtjVrcQMUrU87dUh/view?usp=sharing

<img width="755" height="398" alt="Power BI Dashboard" src="https://github.com/user-attachments/assets/f182a3f7-0710-4cd1-aaeb-ec034266e1ce" />






