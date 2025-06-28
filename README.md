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
  - Attrition by Average Monthly Income (Bar)
  - Employee Count by Age Band and Gender (Column)
  - Job Satisfaction by Rating (Matrix)
  - Attrition Rate by Gender & Age Group (Donut)
- **Slicers** for Education Field.
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
I’m an aspiring Data Analyst currently building hands-on projects to enhance my skills in Power BI, Excel, and SQL. This is one of my first Power BI dashboards, and I'm always open to feedback or collaboration opportunities.


---

📫 Feel free to connect or reach out:
- GitHub: [Haraszmai](https://github.com/Haraszmai)

---

Thank you for visiting this project!


