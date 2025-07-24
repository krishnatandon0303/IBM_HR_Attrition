# IBM_Attrition_Analysis Using SQL

This project analyzes employee attrition patterns using SQL to help an organization reduce turnover and improve retention strategies. The goal is to uncover *why employees leave*, *which departments are most impacted*, and *what actionable steps can be taken*.

## OBJECTIVES:
- Identify key drivers of employee attrition
- Quantify turnover across departments, age groups, and job levels
- Evaluate the cost of attrition to the company
- Recommend data-driven retention strategies

## TOOLS USED:
## SQL
## DBMS : MySQL
## BI : POWER BI (ADDED SOON)

## 🧩 Database Tables

- `employee_details` – Demographic info like age, employee ID
- `employee_snapshot` – Job stats like attrition flag, income, overtime, years at company
- `job_role` – Job level and department mapping

## 🔍 Key Business Questions & SQL Queries

### Q1. What is the total turnover rate (%)
<img width="1920" height="1020" alt="Screenshot 2025-07-24 063846" src="https://github.com/user-attachments/assets/548ee7a0-9456-4f60-9339-6a66545a7c6f" />
# Key Insights: 
Overall turnover rate is ~17.57%, a red flag for HR, especially in competitive industries.

### Q2.Find the total number of employees from each departments who stayed in same company more than 5 years with lest than 20% salary hike
<img width="1920" height="1020" alt="Screenshot 2025-07-24 064030" src="https://github.com/user-attachments/assets/c4d63d21-0726-43b8-9379-adf1f7560064" />
# Key Insights:
Department-wise Attrition Rate:

Sales: 20.63% (highest)

Human Resources: 19.05%

### Q3.What is the attrition rate per department?
<img width="1920" height="1020" alt="Screenshot 2025-07-24 064150" src="https://github.com/user-attachments/assets/07be084e-a41e-4b21-a986-b13addd07343" />
# Key Insights:
High Retention in R&D:
R&D retains the most long-tenured employees (378 people with >5 years experience and <20% hike).

### Q4. Is Low pay causing the quits? || pay vs attrition by departments
<img width="1920" height="1020" alt="Screenshot 2025-07-24 064303" src="https://github.com/user-attachments/assets/2d13ad95-8f97-4459-aea5-220467745266" />
# Key Insights:
Sales quitters earn less than department average, indicating low income may be a factor.

### Q5. Are employees who work overtime are more likely to attrite, and does this vary by job level?
<img width="1920" height="1020" alt="Screenshot 2025-07-24 064510" src="https://github.com/user-attachments/assets/2359adbd-28fc-4d07-a834-09ba16ddefe7" />
# Key Insights:
52.5% of entry-level and 17.8% of associate-level employees with overtime leave — showing OT is linked to burnout and exits.

### Q6. Are New hires quitting quickly?

<img width="1920" height="1020" alt="Screenshot 2025-07-24 064620" src="https://github.com/user-attachments/assets/6a08a6e8-8dfa-4963-af7f-4ab78d68be75" />
# Key Insights:
35% of employees leave within the first year of joining.

### Q7.Attrition by age||Loosing younger or older employees more?
<img width="1920" height="1020" alt="Screenshot 2025-07-24 064837" src="https://github.com/user-attachments/assets/e8e286a2-405b-449f-89c7-6b17559b4112" />
# Key Insights:
18–25 age group shows ~39% attrition, highest among all age bands.

### Q8. Why are Younger hirers leaving, does is cause by low job satisfaction?
<img width="1920" height="1020" alt="Screenshot 2025-07-24 064915" src="https://github.com/user-attachments/assets/d87068fb-2174-4b07-9f47-48cea365b4e7" />
# Key Insights:
Employees with very low satisfaction (rating 1) show 22.84% attrition,
while those with high satisfaction (rating 4) show only 11.33%.

### Q9. What is the total financial impact of attrition to company?
<img width="1920" height="1020" alt="Screenshot 2025-07-24 065109" src="https://github.com/user-attachments/assets/03213e65-19a6-4064-b199-e08eae56ec9c" />
# Key Insights:
Total attrition cost is ~₹2.28 million, assuming replacement cost is 2× monthly income.

### Q10. Which departments are most expensive to replace?
<img width="1920" height="1020" alt="Screenshot 2025-07-24 065109" src="https://github.com/user-attachments/assets/094b4953-a68e-4d39-bfda-0ba3b3418f84" />
# Key Insights:
-- R&D: ₹1,092,748
-- Sales: ₹1,087,156
 These two alone make up over 90% of total attrition cost

--------------------------------------------------------------------------------------------------------


