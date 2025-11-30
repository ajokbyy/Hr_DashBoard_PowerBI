# 📊 HR Employee Attrition & Workforce Analytics Dashboard  
### 🚀 Powered by Microsoft Power BI

<p align="center">
  <img src="https://img.shields.io/badge/PowerBI-Analytics-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-HR_Analytics-blue?style=for-the-badge" />
</p>

---
## ✨ ScreenShort

<img src="https://github.com/ajokbyy/Hr_DashBoard_PowerBI/blob/main/DashBoardByPowerBi.png" height="40" alt="C" />
---

## 📌 Overview  
This project presents a **complete HR Attrition Analytics Dashboard** built using **Power BI**.  
It analyzes employee turnover patterns, departmental trends, income-level risks, and demographic-based attrition.

The dashboard includes interactive KPIs, filters, and visual insights designed for HR decision-making.

---

## 📁 Dataset Information  
| Feature | Details |
|--------|---------|
| **Dataset Name** | HR Employee Attrition Dataset |
| **Records** | 588 employees |
| **Columns** | 35 (cleaned to ~31) |
| **Source** | IBM HR Analytics Sample Dataset |

### 📊 Dataset Contains:
- Demographics (Age, Gender, Education)
- Job roles & departmental details
- Salary & experience
- Performance indicators
- Attrition status (Yes/No)

---

## 🛠️ Tech Stack  
- **Power BI Desktop**  
- **DAX** (for KPIs & measures)  
- **Power Query** (data cleaning & transformations)

---

## ✨ Key Dashboard Features  

### 🔹 KPIs  
- Total Employees  
- Employees Left  
- Attrition Rate  
- Avg Monthly Income  
- Avg Years at Company  

### 🔹 Visualizations  
- Attrition by Department  
- Attrition Rate by Job Role  
- Attrition by Gender  
- Attrition by Income Band  
- Employee Count by Hire Year  

### 🔹 Filters / Slicers  
- Department  
- Job Role  
- Age Group  
- OverTime  

---

## 🧹 Data Preparation  
### ✔ Cleaning  
- Removed irrelevant fields (EmployeeCount, Over18, etc.)  
- Standardized data types  
- Checked for duplicates and missing values  

### ✔ Transformation  
Custom columns created:
- Attrition Flag (0/1)  
- Age Group brackets  
- Income Band  
- HireYear (2025 - YearsAtCompany)  
- HireDate (converted using DAX)

---

## 🔍 Insights Summary  
- The organization has an attrition rate of **15%** (87 employees left).  
- Highest attrition appears in **Sales** and **Research & Development**.  
- Employees aged **26–35** are most likely to leave.  
- Attrition is significantly higher among **low-income employees (<₹4K)**.  
- Those working **OverTime** show a higher tendency to resign.  
- Certain job roles like **Sales Executive** & **Laboratory Technician** show elevated risk.

---

## 📂 Project Structure  
```
📁 HR-Attrition-Dashboard
│── HR_Attrition_Dashboard.pbix
│── HR-Employee-Attrition.csv
│── README.md
```

---

## ▶️ How to Use  
1. Clone the repo:  
   ```bash
   git clone <your_repository_link>
   ```
2. Open **HR_Attrition_Dashboard.pbix** in Power BI.  
3. Use slicers & visuals to explore insights.  

---

## 👨‍💼 Author  
**Abhiraj Singh Chouhan**  
B.Tech CSE (Data Science)

📧 Email: *your email here*  
🌐 Portfolio: *your link here*

---

<h3 align="center">⭐ If this project helped you, consider giving it a star on GitHub!</h3>
