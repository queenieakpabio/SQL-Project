Data Analyst Job Market Analysis — SQL Project
Overview
This project explores the data analyst job market using SQL to answer practical questions about which roles pay the most, which skills are most in demand, and which skills offer the best combination of demand and salary. The analysis is designed to help data analysts make smarter decisions about which skills to develop.

The dataset used is a real-world job postings dataset containing information on roles, salaries, companies, skills, and work arrangements sourced from job listings across the globe.


Questions Analysed
What are the top-paying remote Data Analyst jobs?
What skills are required for the top-paying Data Analyst jobs?
What skills are most in demand for remote Data Analyst roles?
Which skills are associated with higher average salaries?
Which skills are both highly demanded and well-compensated — the optimal skills to learn?


Tools Used
PostgreSQL / SQL — all analysis written in SQL
CTEs (Common Table Expressions) — used in Query 2 to filter top-paying jobs before joining on skills
JOINs — LEFT JOIN, INNER JOIN across three related tables
Aggregations — COUNT, AVG, ROUND for demand and salary analysis
HAVING — used in Query 5 to filter skills with meaningful sample sizes (more than 10 job postings)
ORDER BY / LIMIT — for ranking and focusing results


Project Structure
SQL-Project/

│

├── 1_top_paying_jobs.sql          -- Top 10 highest-paying remote Data Analyst roles

├── 2_top_paying_jobs_skills.sql   -- Skills required for those top-paying roles

├── 3_top_demanded_skills.sql      -- Top 5 most in-demand skills for remote DA roles

├── 4_top_paying_skills.sql        -- Top 25 skills ranked by average salary

└── 5_optimal_skills.sql           -- Skills that are both high-demand and high-paying
