# 💼 Salary & Experience Across Global Industries  
### **Milestone-1 Project | End-to-End Data Analysis**

This project analyzes global salary survey data to understand how **experience**, **job titles**, **industries**, **education**, and **locations** influence compensation.  
It follows a complete workflow from **data cleaning → MySQL → SQL queries → Excel dashboard → Insights**.

---

# 📊 **Dataset Attributes**
The dataset includes the following fields:

- **Age Range**  
- **Industry**  
- **Job Title**  
- **Clarification of Job Title**  
- **Annual Salary**  
- **Additional Monetary Compensation**  
- **Currency** / **Other Currency**  
- **Income Clarification**  
- **Country**, **State**, **City**  
- **Years of Professional Experience (Overall)**  
- **Years of Experience in Field**  
- **Highest Level of Education Completed**  
- **Gender**

---

# 🧹 **Step 1: Data Cleaning & Preprocessing**

### ✔ Handle Missing Values  
- Numeric columns → mean/median replacement or row removal  
- Categorical columns → replace with **"Unknown"** or remove  

### ✔ Standardize Data Types  
- Convert salary to numeric  
- Convert experience fields to integers  
- Ensure categorical fields use consistent formatting  

### ✔ Handle Inconsistent Values  
- Normalize job titles ("Researcher" vs "researcher")  
- Standardize country names ("USA" vs "United States")  
- Fix capitalization inconsistencies  

### ✔ Outlier Detection  
- Detect extreme values in salary  
- Remove or adjust unrealistic values  

### ✔ Final Output  
A cleaned dataset saved as:  
`salary_survey_cleaned.csv`

---

# 🛢️ **Step 2: Importing Data Into MySQL**

### ✔ Create Database  
```sql
CREATE DATABASE salary_survey;
USE salary_survey;
✔ Create Table

A table with proper data types for each column.

✔ Import Data

Using either LOAD DATA INFILE or MySQL Workbench Import Wizard.

🧮 Step 3: SQL Queries for Dashboard Creation
1️⃣ Average Salary by Industry & Gender

Shows gender-based salary differences.

2️⃣ Total Compensation by Job Title

Sum of salary + extra compensation.

3️⃣ Salary Distribution by Education Level

(Avg, Min, Max) grouped by education.

4️⃣ Number of Employees by Industry & Experience

Counts employees by experience brackets.

5️⃣ Median Salary by Age Range & Gender

Insight into salary age patterns.

6️⃣ Highest Salary Job Title per Country

Useful for international comparisons.

7️⃣ Average Salary by City & Industry

City-wise earning patterns.

8️⃣ Percentage Receiving Extra Compensation by Gender

Bonus and perks analysis.

9️⃣ Total Compensation by Job Title & Experience

Experience-driven salary trends.

🔟 Salary by Industry, Gender & Education Level

Multi-factor salary comparison.

All SQL outputs exported as CSV.

📄 Step 4: Excel Tables

Each SQL query result imported into separate Excel sheets:

Sheet1 → Avg Salary by Industry & Gender  
Sheet2 → Total Compensation by Job Title  
Sheet3 → Salary by Education  
Sheet4 → Employees by Experience  
...  
Sheet10 → Salary by Industry + Gender + Education

 Step 5: Dashboard Creation (Excel)
✔ Pivot Tables created for:

Salary distribution

Gender distribution by job title

Industry salary comparison

Compensation breakdown

✔ Dashboard Visuals:

Bar charts

Line charts

Donut charts

Slicers for industry, gender, experience

✔ Final Dashboard Includes:

Top-paying job titles

Salary by industry

Gender comparison

Education vs salary

Compensation insights

📘 Deliverables

✔ Cleaned dataset

✔ MySQL database & table

✔ 10 SQL query outputs (CSV)

✔ Excel file with 10 sheets

✔ Excel dashboard

✔ Documentation PDF

✔ 10–slide presentation

 Key Insights

Experience strongly impacts salary growth.

Tech & Finance industries show highest compensation.

Senior roles earn ~3–5x more than junior roles.

Education level influences salary but varies by industry.

Additional bonuses more common among certain genders/roles.

Cities in developed countries offer higher compensation ranges.

 Conclusion

This Milestone-1 project demonstrates:

✔ Data cleaning & preprocessing
✔ MySQL workflow
✔ SQL analytics
✔ Excel reporting & dashboard creation
✔ Industry-level documentation & presentation

A complete end-to-end data analysis solution.
 

Project documentation

PPT presentation
