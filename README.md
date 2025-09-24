# HR Data Analytics

## 📌 Project Overview  
This Power BI report provides a comprehensive analysis of **employee performance, attrition trends, and store productivity**.  
It is designed to support decision-making by combining workforce analytics with operational KPIs across 150 stores.  

The report consists of **two pages**:  
1. **Employee Insights**  
2. **Store & Productivity Insights**  


## About the Data
As a HR data analyst working with a comprehensive dataset of over 497,000 detailed employee performance records. The goal is to analyze workforce patterns and uncover actionable insights that HR teams and business leaders can use to improve employee satisfaction, optimize performance, and enhance organizational effectiveness.

In this dataset, you'll explore a professional HR management system that includes attributes and metrics such as:

•	Employee demographics, education level, job roles, and organizational hierarchy

•	Performance ratings, training hours, overtime, absenteeism, and engagement metrics

•	Compensation data including salaries, bonuses, and benefits costs

•	Manager relationships, promotion flags, and career progression indicators

•	Store locations, departments, employment types, and business outcomes

•	Monthly performance tracking across 3 years (2022-2024)

•	Role-specific KPIs, productivity indices, and customer satisfaction scores


## Technical Requirements
1. How many employees left the company? Which department has the most people leaving?
2. What is the average salary by job level? Create a chart showing salary differences between departments.
3. Which months have the highest employee performance ratings? Show this in a graph.
4. Who are the top 10 managers based on their team's average performance scores?
5. Do employees who get more training hours have better performance ratings? Show the relationship.
6. Which 5 stores have the highest sales? What makes them different from low-performing stores?
7. What is the average employee satisfaction score by department? Which department is happiest?
8. Compare the productivity index across different job roles. Which roles are most productive?
9. Which employees are most likely to get promoted based on their performance and satisfaction scores?
10. What is the relationship between employee age and performance rating? Do younger or older employees perform better?


## 🧩 Page 1 – Employee Insights  

### 🎯 Purpose  
Analyze workforce dynamics, focusing on demographics, attrition, and performance.  

### 🔑 KPIs  
- Attrition Rate (%) – overall and by department  
- Average Performance Rating  
- Training Hours per Employee  
- Employee Count  

### 📈 Visuals  
- Attrition by Department (bar chart)  
- Max/Min Attrition Rate by Department (KPI cards)  
- Age vs Performance (scatter plot with age groups)  
- Performance vs Training Hours (matrix with conditional formatting)  

<img width="746" height="418" alt="image" src="https://github.com/user-attachments/assets/56567c8d-62ae-4865-b04e-f8a6464b516b" />


## 🧩 Page 2 – Store & Productivity Insights  

### 🎯 Purpose  
Track **store-level performance, sales contribution, and operational KPIs**.  

### 🔑 KPIs  
- Total Sales & Breakdown by Store Type  
- On-Time Delivery %  
- Customer Satisfaction (1–10 scale)  
- Waste/Loss % (highlight highest & lowest)  

### 📈 Visuals  
- Top 5 / Bottom 5 Stores (matrix with Store ID, Sales, Satisfaction, Training Hours)  
- Sales by Store Type (pie/bar chart with % contribution)  
- Waste/Loss % Trend (line chart with conditional colors)  
- Dynamic Card → “Sales across [Store Type] – [No. of Stores] – [Share of Total Sales]”

  <img width="746" height="419" alt="image" src="https://github.com/user-attachments/assets/c6d76cc4-dd5c-42d7-8cf7-1a9eaad238fe" />


## 🛠️ Data Model  
- **Employees Table** – Employee demographics, training  
- **Performance Table** – Monthly ratings, satisfaction  
- **Stores Table** – Store ID, type, sales, delivery, waste/loss  

Relationships:  
- Employees → Performance (1-to-many)  
- Stores → Metrics (1-to-many)  
