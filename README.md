# 🎓 MS Elevate - AICTE Power BI Internship (4 Weeks)

Welcome to my repository for the **Microsoft Elevate Virtual Internship** program! This project showcases the end-to-end Business Intelligence workflow developed over 4 weeks under the guidance of **Microsoft** and **Edunet Foundation**.

---

## 🌟 Internship Highlights
- 🏛️ **Portal:** [AICTE National Internship Portal (Official Registration)](https://internship.aicte-india.org)
- 💻 **Platform:** [Elevate | FICE Education (Learning & Project Hub)](https://elevate.fice.in/)
- 🕒 **Duration:** 4 Weeks (Intensive Learning)
- 🛠️ **Core Focus:** Data Analytics, ETL, DAX, and Data Storytelling
- 📜 **Certification:** Microsoft Elevate & AICTE Recognized

---

## 📅 Weekly Progress Roadmap

### 🔍 Week 1: Introduction to Data Analysis & Data Transformation

**🛠️ Session-1 : Understanding the Data Analyst role, Business Intelligence (BI) foundations, and the Power BI ecosystem.**
*   **Key Learning Modules:**
    *   **Data Analytics Essentials:** Definition, importance, and the 5-step process: **Collection $\rightarrow$ Cleaning $\rightarrow$ Analysis $\rightarrow$ Interpretation $\rightarrow$ Decision Making**.
    *   **Analytical Types:** Deep dive into **Descriptive** (What happened?), **Diagnostic** (Why did it happen?), **Predictive** (What could happen?), and **Prescriptive** (What should we do?) analytics.
    *   **BI vs. Data Analytics:** Comparing focus areas (Historical Trends vs. Future Predictions), tools, and target users (Business Executives vs. Data Scientists).
    *   **Power BI Setup:** Installation of **Power BI Desktop** and understanding the core `.pbix` workflow (Connect $\rightarrow$ Transform $\rightarrow$ Model $\rightarrow$ Visualize).
    *   **Industry Applications:** Exploring how **Healthcare, Finance, and Retail** leverage data for competitive advantage and operational optimization.

         <img width="1496" height="666" alt="image" src="https://github.com/user-attachments/assets/772748a6-2ddc-4ab4-9d5c-867f72d82fc3" />
      
**🛠️ Session-2: ETL & Data Cleaning (Power Query).**
  In this session, I processed three years of raw sales data (2018–2020) to create a clean, analysis-ready dataset.
 *   **Data Consolidation:** Appended and merged separate datasets for 2018, 2019, and 2020 into a single unified "Order Details" master table.
 *   **Text & Format Standardization:** Used Capitalized Each Word for consistency and Split Columns by Character to extract specific data attributes for deeper granularity.
 *   **Structural Optimization:** Streamlined the table schema by Removing, Renaming, and Reordering columns to ensure a logical and user-friendly data structure.
 *   **Feature Engineering:** Utilized the Inserted Year transformation to enable time-series filtering and Year-over-Year (YoY) performance comparisons

   <img width="1920" height="1020" alt="OrderDetails" src="https://github.com/user-attachments/assets/b9cc1ee6-7bd8-4c6b-be22-5ff623dff7bd" />

***
### 📊 Week 2: Relational Modeling & Star Schema

**🛠️ Session 3: Financial Analysis & Executive Reporting**
*   **Automated Date Modeling:** Created a dedicated Calendar Table to establish a robust relationship with financial data for time-series analysis.
*   **Executive Summary Dashboard:** Designed a high-impact financial report featuring a sleek dark-themed UI for better readability and focus.
*   **Advanced Visualizations & KPIs:**
      *   **Financial Metrics:** Tracked $118.73M in Total Sales and 1M Units Sold using dynamic KPI cards.
      *   **Geographic & Product Insights:** Utilized Funnel charts for country-wise profit analysis and Pie charts for product distribution (e.g., Paseo leading at 202 units).
      *   **Segment Performance:** Implemented a Treemap to visualize market dominance, identifying "Government" as the top-performing segment.
*   **Interactive Navigation:** Integrated Slicers (Month/Year) to allow end-users to drill down into specific timeframes dynamically.
    <img width="1126" height="631" alt="Financial Report" src="https://github.com/user-attachments/assets/303d6ae6-3f0d-4cbe-ae36-2572dd10248b" />

**🛠️ Session-4: Complex Data Modeling (Star Schema)**
*   **7-Table Integration:** Processed and cleaned a relational database consisting of Customer, Date, Product, Reseller, Sales, SalesOrder, and SalesTerritory.
*   **Star Schema Architecture:** Designed a professional data model by connecting a central Fact Table (Sales) to multiple Dimension Tables.
*   **Relationship Management:** Established One-to-Many and One-to_One relationships and optimized cross-filter directions for accurate calculation.
*   **Insights:** Integrated global mapping, product performance bar charts, hierarchical financial matrices, and monthly sales trends to highlight regional volume, top-selling categories, and seasonal growth peaks.
*   **Interactivity:** Added a hierarchical Date Slicer (Year/Month) allowing users to toggle between 2017 and 2018 data instantly.
    <img width="1920" height="1080" alt="Sales_datamodeling" src="https://github.com/user-attachments/assets/3f22dc91-dd19-433f-84d4-b300c13fcdea" />
    <img width="1042" height="586" alt="Sales_Report" src="https://github.com/user-attachments/assets/710c36c7-f4cc-4430-9aa2-062dd2c620d6" />
***
### 👥  Week 3:  Employee Data ETL

**🛠️ Session-5: Employee Data Transformation & Profiling**
*   **Employee Data Transformation:** Performed end-to-end ETL on Employee data, ensuring 100% data validity through rigorous Column Quality profiling in Power Query.
*   **KPI Development:** Calculated critical workforce metrics including Total Enrolled Employees (38), Present/Absent counts, and an 87% Average Attendance rate.
*   **Interactive Dashboard:** Workforce Distribution: Used a Treemap to visualize employee counts by Job Level (Analyst, Executive, etc.).
      *   **Organizational Hierarchy:** Developed a Treemap to categorize headcount by Job Level, identifying "Analyst" and "Team Lead" as primary roles.
      *   **Managerial & Team Productivity:**  Designed Stacked Column Charts to visualize the "Absent vs. Present" ratio across 5 distinct teams and individual managers.
      *   **Demographic & Reporting Insights**  Integrated Donut Charts to monitor gender diversity (58% Male / 42% Female) and span of control for managers.
        <img width="1380" height="732" alt="Home_report_EmployeeData" src="https://github.com/user-attachments/assets/88e5a500-7d14-49f5-8ae9-e03168f7cc56" />

**🛠️ Session-6: Compensation Analysis & Advanced Data Transformation**
*   **Custom Column (Power Query):** Created emp_salary by calculating Salary + Bonus for total compensation tracking.
*   **Salary KPI Dashboard:**
    *    **Financials:** Tracked critical metrics including Max Salary (₹47,250), Min Salary (₹10,500), and Total Payroll (₹7,25,550).
    *    **Top Talent Insights:** Visualized the "Top 10 Employees By Salary," identifying Kevin Tony as the highest-paid individual at ₹38,325.
    *    **Level-Based Benchmarking:** Analyzed Avg Salary By Job Level, highlighting that "Analysts" currently hold the highest average compensation at ₹29,925.
*   **Interactive UI:** Added a "Reset Slicers" button and multiple filters (Team, Job Level, Manager) for deep-dive analysis.

    <img width="1920" height="1080" alt="PowerQuery2" src="https://github.com/user-attachments/assets/9eac6178-8626-4559-8883-fe4eba4b9152" />
    
    <img width="1286" height="718" alt="Salary_report_EmployeeData" src="https://github.com/user-attachments/assets/a79de0d7-2a44-4089-bee4-71d9f5c64c15" />

---

### 🏛️ Week 4: Capstone Project – PMAY-G & Social Convergence Analysis

**🛠️ Final Project: End-to-End Analysis of Pradhan Mantri Awaas Yojana-Gramin (PMAY-G)**
For the final week, I transitioned from synthetic business data to a massive, real-world public dataset. I developed a multi-page interactive report to track the progress, efficiency, and social impact of India's rural housing mission.

*   **Integrated Multi-Source ETL:** Cleaned and modeled three distinct datasets: Housing Completions, Administrative Lead Times, and Swachh Bharat (SBM) / Ujjwala (LPG) convergence data.
*   **Key Analytical Dashboards:**
    *   **Project Overview:** Tracked **Total Sanctioned vs. Completed** units with a dynamic trend line identifying the 2016-17 construction surge.
    *   **Efficiency Audit:** Built a "Lead Time" analysis page to identify bottlenecks in the **Admin $\rightarrow$ Construction $\rightarrow$ Transaction** lifecycle across different states.
    *   **Social Convergence:** Utilized a **Funnel Visual** to track how effectively housing beneficiaries were being "seeded" into other government schemes like clean energy (Ujjwala) and sanitation (SBM).
*   **Advanced Modeling:** Implemented a **Star Schema** with a centralized `Dim_State` table to ensure consistent filtering across disparate housing and sanitation fact tables.
*   **Insights:** Identified Bihar and Madhya Pradesh as volume leaders, while highlighting a significant gap in sanitation (SBM) seeding that requires administrative intervention.
  
    <img width="1117" height="628" alt="Overview" src="https://github.com/user-attachments/assets/9e0cc93f-0aba-400f-9635-dc2f163656d6" />

    <img width="1183" height="666" alt="Efficiency Audit" src="https://github.com/user-attachments/assets/51aa54d4-e8d6-4de3-b39f-7a32798abd84" />

    <img width="1182" height="663" alt="Convergence" src="https://github.com/user-attachments/assets/52f625df-454a-4059-8980-3719ae5f9117" />

    <img width="1211" height="663" alt="Data Modeling" src="https://github.com/user-attachments/assets/b1295454-6cc1-43c3-8d6a-6f91da282e60" />

    <img width="1920" height="1025" alt="PowerQuery 1" src="https://github.com/user-attachments/assets/63062e9a-bdf0-4822-9e22-e6919ab8ba4f" />

    <img width="1920" height="1025" alt="PowerQuery2" src="https://github.com/user-attachments/assets/017f7ad5-47a0-4719-ab6e-18480bcdc5e6" />

    <img width="1920" height="1018" alt="PowerQuery3" src="https://github.com/user-attachments/assets/1cbf3a98-f527-41c0-b806-7b800fe64410" />

--- 
## 🤝 Let's Connect!
If you have any feedback or want to discuss Power BI, feel free to reach out!

https://www.linkedin.com/in/swaranjali-harkare-364a592a8/
