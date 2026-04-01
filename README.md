# HR-performance-Dashboard-integrating-Sql-and-excel
# COMPANY : CODETECH IT SOLUTIONS
# Name : Prajakta Sujit Sawant
# Intern id : CTIS6799
# Domain : Power BI
# Duration : 4 Weeks
# Mentor : Neela Santosh
# Description : HR Employee Performance & Training Insights Dashboard


🔹 Project Overview

The HR Employee Performance & Training Insights Dashboard is an interactive Power BI report designed to analyze employee performance, salary trends, project completion, and training activities. <br>
This dashboard integrates data from MySQL and Excel, providing a centralized platform for HR teams to monitor workforce productivity and training effectiveness.<br>
It helps organizations make data-driven HR decisions by offering insights into hiring trends, employee performance, and skill development. <br>


🎯 Objectives <br>
* Monitor employee performance and productivity.<br>
* Analyze salary distribution across departments.<br>
* Track project completion metrics.<br>
* Evaluate training effectiveness.<br>
* Understand hiring trends over time.<br>

📈 Key Insights <br>
📌HR and Sales departments completed the highest number of projects.<br>
📌Average employee performance rating is 3.05 (moderate performance level) <br>
📌 Peak hiring observed around **mid-year (July–August)** <br>
📌 Training completion rate shows a balanced distribution, but **some employees are still in progress** <br>
📌 Courses like **Data Analysis & Leadership** have the highest training hours <br>
📌 Salary distribution indicates variation across departments <br>


⚙️ Tools & Technologies Used

**Power BI Desktop** → Dashboard development.<br>
* **MySQL** → Primary database source.<br>
* **Microsoft Excel** → Additional dataset (training records).<br>
* **Power Query** → Data extraction, cleaning & transformation.<br>
* **DAX (Data Analysis Expressions)** → Calculations & measures.<br>


Data Integration (MySQL + Excel)

 1. MySQL Connection<br>
* Connected Power BI to MySQL database <br>
* Imported employee performance data using:<br>
  * Server connection<br>
  * Database selection<br>


2. Excel Connection<br>
* Imported training dataset from Excel<br>
* Cleaned and structured training-related data<br>


3. Data Merging<br>
* Combined MySQL and Excel datasets using:<br>
* Common keys (Employee ID)**<br>
* Built relationships in data model<br>


🛠️ Task Implementation (How It Was Performed)

Step 1: Data Preparation<br>
* Loaded data from:<br>
  * MySQL (Employee data)<br>
  * Excel (Training data)<br>
* Cleaned data:<br>
  * Removed null values<br>
  * Standardized columns<br>
  * Changed data types<br>


Step 2: Data Modeling

* Created relationships between:<br>
  * Employee table<br>
  * Training table<br>

Step 3: DAX Calculations

Created measures such as:<br>
* Total Employees<br>
* Average Salary<br>
* Avg Performance Rating<br>
* Total Training Hours<br>
* Projects Completed<br>

Step 4: Advanced Features Used

✅ Slicers (Filters)<br>
* Hire Date<br>
* Department<br>
* City<br>
* Course Name<br>

✅ Parameter (Metric Selector)

* Dynamic switching between:<br>
  * Average Salary<br>
  * Performance Rating<br>
  * Employee Count<br>
  * Project Completed<br>

✅ Conditional Formatting (Table)<br>
* Applied on:<br>
  * Performance Rating (icons/colors) <br>
  * Salary (data bars)

🚀 Conclusion

This dashboard provides a holistic view of HR operations, enabling organizations to:<br>
* Track employee performance<br>
* Improve training programs<br>
* Optimize hiring strategies <br>
* Enhance workforce productivity

OUTPUT :
<img width="1628" height="692" alt="image" src="https://github.com/user-attachments/assets/be00d5e3-721c-4e29-b43d-8fd847139766" />
