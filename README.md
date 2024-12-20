# BigData Test Project
# Data Science Salary Analysis
This repository contains the analysis of salaries for various data science-related positions across different years, experience levels, employment types, and company sizes. The analysis is based on a dataset containing information about employee salaries in the tech industry.

Project Overview
The goal of this analysis is to explore and understand how various factors such as experience level, job title, employment type, and company size affect the salaries of employees in data science roles.

Dataset Description
The dataset includes the following columns:

work_year: The year the data was collected.
experience_level: The experience level of the employee (0 - Entry, 1 - Mid, 2 - Senior, 3 - Executive).
employment_type: The type of employment (FT - Full Time, PT - Part Time, CT - Contract, FL - Freelance).
job_title: The title of the employee's job.
salary: The salary offered in the employee's local currency.
salary_currency: The currency of the salary.
salary_in_usd: The salary converted to USD.
employee_residence: The country where the employee resides.
remote_ratio: The percentage of remote work allowed by the company.
company_location: The location of the company.
company_size: The size of the company (S - Small, M - Medium, L - Large).
Analysis and Visualizations
Key Insights:
Salary Distribution: The salary distribution has a wide range, from $5,132 to $450,000, with a mean of $137,570.
Experience Level: Higher experience levels tend to correlate with higher salaries. Senior and Executive roles typically earn the most.
Employment Type: Full-time employees tend to earn higher salaries compared to part-time or freelance workers.
Company Size: Larger companies generally offer higher salaries than small companies.
Remote Work: Employees with a 100% remote work ratio tend to earn slightly higher salaries compared to those working on-site.
Visualizations
Salary Distribution: A histogram and a boxplot were used to show the distribution of salaries in USD.
Experience Level vs. Salary: A boxplot compares salaries across different experience levels.
Employment Type vs. Salary: Boxplots and bar charts show salary distributions for different types of employment.
Company Size vs. Salary: A boxplot reveals how company size influences salary.
Statistical Tests
We conducted ANOVA tests to check whether experience level and employment type significantly affect salaries. Both tests showed significant differences in salaries based on these variables.

Installation
Clone the repository:

bash
Kodu kopyala
git clone https://github.com/yourusername/SalaryAnalysis.git
Install the required dependencies:

bash
Kodu kopyala
pip install -r requirements.txt
Run the analysis:

bash
Kodu kopyala
python salary_analysis.py
Usage
Once the dependencies are installed, you can run the analysis scripts to generate insights, visualizations, and statistical tests. All plots will be displayed using matplotlib and seaborn.

Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

