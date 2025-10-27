Introduction

The purpose of this project is to analyze the job market for Data Analyst roles using the given dataset. The dataset contains information such as job titles, salaries, company ratings, locations, industries, and job descriptions. By exploring this data, we can understand which companies and industries hire the most, where the highest demand is, and what skills are most commonly required for Data Analyst positions.

The analysis focuses on answering key questions such as:
- How many Data Analyst jobs exist in this dataset?
- Which job titles, companies, and locations dominate the market?
- What industries are hiring the most?
- Which skills appear most frequently in job descriptions?

🧹 Data Cleaning

Before analyzing the data, several steps were taken to ensure accuracy and usability:
- Removed duplicate records to avoid counting the same job multiple times.
- Handled missing values by removing rows with essential missing data (like job title or company name) and keeping non-essential missing values for analysis context.
- Dropped irrelevant columns such as Competitors and Easy Apply due to excessive missing data (-1 values in most rows).
Standardized column formats by:
- Converting salary to numeric format where possible.
- Cleaning text columns (removing extra spaces, converting to lowercase for skill extraction).
- Filtered for Data Analyst-related roles to ensure the analysis focuses only on relevant job listings.

📊 Exploratory Data Analysis (EDA)

Key findings from the dataset include:
1. Total Data Analyst Jobs: 2,253 job listings match Data Analyst-related roles.
2. Unique Job Titles: 1,272 different job titles exist, suggesting a wide variety of specializations.
3. Most Common Job Titles: The top three roles are Data Analyst, Senior Data Analyst, and Junior Data Analyst.
4. Companies Hiring the Most:
- Staffigo Technical Services LLC (Rating: 5.0)
- Diverse Lynx (Rating: 3.0)
- Kforce (Rating: 4.0)
5. Top Locations for Data Analyst Jobs: New York, NY; Chicago, IL; San Francisco, CA.
6. Salary Insights: Most job listings fall within similar pay ranges ($37K–$66K or $46K–$87K), indicating standardized pay bands across companies for Data Analyst roles in this dataset.
7. Industries Hiring the Most: IT Services and Staffing & Outsourcing dominate hiring, though there is a large portion of missing industry data (-1).
8. Top Skills in Job Descriptions:
- SQL
- Reports
- Communication
- Tableau
- Python
- Dashboards
- Machine Learning
- BI Tools
- MS Office
- Data Visualization

💡 Recommendations

- Include posting dates – Allows trend analysis to identify hiring peaks and seasonal demand.
- Reduce missing data – Especially in the Industry, Easy Apply, and Competitors columns to enable more complete analysis.
- Capture remote/on-site information – Helps target remote talent pools and adjust recruitment policies.
- Include skill proficiency levels – To identify not just what skills are needed, but at what depth (e.g., beginner, intermediate, advanced).

✅ Conclusion

- This project provided a clear picture of the Data Analyst job market within the given dataset:
- There are 2,253 job listings with over 1,272 unique job titles, showing high diversity in role naming.
- The market is dominated by a few companies (Staffigo Technical Services LLC, Diverse Lynx, Kforce) and concentrated in major cities (New York, Chicago, San Francisco).
- Most salaries fall into similar bands ($37K–$66K or $46K–$87K), indicating standardized pay for Data Analyst roles.
- Key skills in demand include SQL, Tableau, Python, dashboards, and data visualization.
