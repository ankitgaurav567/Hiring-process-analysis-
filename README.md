# Hiring Process Analytics

This project analyzes hiring data to uncover insights about gender distribution, salary trends, departmental strengths, and job tier distributions using **Microsoft Excel 2021**.

## 📄 Project Description

The dataset consists of 7,168 records with 6 key features related to applicants who were interviewed for different roles. The main goal of the project was to clean, analyze, and visualize the data to support data-driven decision-making in hiring.

**Dataset Columns:**
- `application_id`: Unique ID of the applicant
- `Interview Taken on`: Date and time of interview
- `Status`: Hired or Rejected
- `event_name`: Gender of the applicant
- `Department`: Department the candidate interviewed for
- `Post Name`: Job position offered
- `Offered Salary`: Salary offered for the role

## 🛠 Tools Used
- **Microsoft Excel 2021**

## 🔧 Data Cleaning
- Replaced "-" in gender with "Don't want to say"
- Imputed missing salary values with median of salaries in Sales department
- Standardized Post Name values (e.g., replaced "c-10" with "c10")
- Handled missing Post Name using department + salary bin logic
- Removed 54 duplicate rows using `COUNTIF` + filter
- Identified and handled outliers using boxplot and replaced with departmental medians

## 📊 Key Insights
1. **Gender Ratio**  
   Male hires are higher (~60%) than female hires (~40%), with some applicants not disclosing gender.

2. **Average Salary**  
   Average salary for hired candidates closely matches the overall salary average, indicating consistent and fair salary decisions.

3. **Salary Distribution**  
   Salary bins show fairly even distribution, with a few high outliers (₹200k–₹400k).

4. **Department Distribution**  
   Most employees belong to Operations and Service departments, reflecting company focus on these areas.

5. **Position Tier Breakdown**  
   Positions like C5, C9, I5, and I7 are most common; M6 and N6 are upper-tier management roles.

## 📈 Visualizations
- Pie charts and bar graphs for gender, department, and post name distribution
- Histogram for salary bins
- Boxplot for outlier detection

## 🧠 Learning Outcomes
- Applied practical data cleaning techniques (handling nulls, duplicates, outliers)
- Used Excel functions: `AVERAGE`, `AVERAGEIF`, `MEDIAN`, `FLOOR`, `FILTER`, `COUNTIF`
- Gained hands-on experience with PivotTables and charts
- Understood hiring data trends for actionable HR insights

---

### 🔗 Connect with Me

I'm Ankit Gaurav, a data analyst with expertise in Excel, SQL, and Power BI.  
📧 [ankitgaurav567@gmail.com](mailto:ankitgaurav567@gmail.com)  
🌐 [LinkedIn Profile](https://www.linkedin.com) https://www.linkedin.com/in/ankit-gaurav-18a041165

