# 🧠 IBM HR Analytics Dashboard (Power BI Project)

This project explores employee attrition trends using the IBM HR Analytics dataset. The dashboard was created in **Power BI** to identify key factors contributing to employee turnover and provide actionable insights for HR decision-making.

---

## 📊 Project Objective

To analyze employee attrition and understand how factors such as department, job role, gender, age group, and education field affect employee turnover.

---

## 🧷 Dataset Information

- **Source**: [IBM HR Analytics Employee Attrition & Performance – Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Total Records**: 1,470 employees
- **Main Columns**: Attrition, Age, Gender, Department, Job Role, Business Travel, Monthly Income, Total Working Years, etc.

---

## 🛠️ Tools & Techniques

- **Power BI Desktop**
- Power Query (Data Cleaning & Transformation)
- DAX (Calculated Columns & Measures)
- Data Modeling (Star Schema)
- Custom Visualizations (Pie, Bar, Matrix, Card, Slicers)

---

## 🧹 Data Preparation

- Converted binary values (`Yes/No`) to `1/0` (e.g. Attrition, OverTime).
- Created new column: `Age Band` with ranges:
  - Under 25
  - 26–35
  - 36–45
  - 46–55
  - Above 56
- Calculated new measures:
  - `Total Attrition`
  - `Active Employees`
  - `Attrition Rate`
  - `Average Age`
  - `Income Per Year of Experience`
- Built dimension tables for Department, Education Field, Job Role, Business Travel (Star Schema model).

---

## 📌 Key Insights

- Highest attrition occurred in the **Sales** department.
- Age group **26–35** showed the highest attrition.
- Female employees showed higher attrition in some age bands.
- Job satisfaction rating was lower among roles with higher attrition.

---

## 🧩 Dashboard Features

- **KPI Cards**: Total Employees, Attrition Count, Attrition Rate, Active Employees, Average Age.
- **Charts**:
  - Attrition by Department (Pie)
  - Attrition by Education Field (Bar)
  - Employee Count by Age Band and Gender (Stacked Column)
  - Job Satisfaction Matrix by Role
  - Attrition Rate by Gender & Age Group
- **Slicers** for Department, Education Field, and Business Travel.
- Interactive filters and clean, professional design.

---

## 📁 File Structure
📦 IBM-HR-Analytics-Dashboard
┗ 📷 dashboard.pdf
┗ dashboard.png
┗ HR Analytics Dataset
┣ 📄 README.md
---



## 🔚 Conclusion

This dashboard demonstrates how HR departments can leverage data analytics to reduce attrition, identify high-risk groups, and improve employee retention strategies.

---

## 🙋‍♀️ Author
Hi! I'm currently new in the field of data analytics and still learning by building practical projects like this one.  
This is one of my first Power BI projects and I’d really appreciate any **review, suggestions, or constructive feedback** to help me grow.

---

📫 Feel free to connect or reach out:
- GitHub: [YourUsername](https://github.com/Haraszmai)

---

Thank you for visiting this project!


