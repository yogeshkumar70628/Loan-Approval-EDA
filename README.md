#  Loan Approval Data Analysis Project

##  Project Overview
This project focuses on exploratory data analysis (EDA) of a loan approval dataset to uncover patterns, trends, and key factors influencing loan approvals. The analysis includes data cleaning, preprocessing, statistical summaries, and visualizations to derive meaningful business insights.

The goal is to simulate a real-world data analyst workflow and demonstrate strong analytical, visualization, and data-handling skills.

---

##  Objectives
- Clean and preprocess raw dataset  
- Handle missing values effectively  
- Perform univariate and bivariate analysis  
- Identify key drivers of loan approval  
- Generate actionable business insights  

---

## 📂 Dataset Description
The dataset contains information about loan applicants, including:

- Demographics: Gender, Dependents  
- Financial Details: Applicant Income, Co-applicant Income  
- Loan Details: Loan Amount, Loan Term  
- Credit History  
- Loan Status (Target Variable)  

---

##  Tools & Technologies
- Python  
- Pandas – Data manipulation  
- NumPy – Numerical operations  
- Matplotlib & Seaborn – Data visualization  
- SciPy – Statistical analysis  
- Jupyter Notebook  

---

##  Data Preprocessing
- Handled missing values using:
  - Mode for categorical variables  
  - Median for numerical variables  
- Verified dataset integrity using:
  - `.info()`  
  - `.isna().sum()`  

Result: Clean dataset with no null values.

---

##  Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Histograms to analyze distributions  
- Boxplots to detect outliers  
- Bar charts and pie charts for categorical insights  

### 🔹 Bivariate Analysis
- Scatter plots to explore relationships between:
  - Income vs Loan Amount  
  - Credit History vs Loan Approval  

---

##  Key Insights
- Most applicants have income between ₹5,000 – ₹10,000  
- Income shows high variability with outliers  
- Male applicants dominate (~81%)  
- Female participation is lower (~19%)  
- Credit history is the most critical factor in loan approval  
- Loan terms are mostly standardized (e.g., 360 months)

---

##  Business Recommendations
- Focus on credit score improvement programs  
- Increase outreach to female applicants  
- Target mid-income groups for loan products  
- Use credit history as a primary decision metric  

---

##  Project Highlights
- Performed end-to-end data analysis on a real-world dataset  
- Applied data cleaning, transformation, and visualization techniques  
- Extracted business insights from structured data  
- Built strong understanding of EDA and statistical analysis  

---

##  How to Run the Project
1. Clone the repository  
2. Open the Jupyter Notebook  
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
4. Run all cells step-by-step  

---

##  Future Improvements 
- Dashboard creation using Power BI or Tableau  

---

##  Author
Yogesh Kumar
Aspiring Data Analyst
