# EDA-on-Data-Science-Job-salaries
In this project, I performed an extensive Exploratory Data Analysis (EDA) on data related to salaries of Data Science jobs. The purpose of this analysis is to understand the factors that influence salary and to gain insights that could guide individuals in their career path.

Data science jobs are some of the fastest-growing, most in-demand in technology. Since 2012, Data Scientist roles have increased by 650 percent, and this rise shows no sign of stopping. The U.S. Bureau of Labor Statistics predicts that the demand for data science skills will increase another 27.9 percent by 2026. And, according to a report from McKinsey, that spells a shortage of between 140,000 and 190,000 people with analytical skills in the U.S. alone—not to mention another 1.5 million managers and analysts who will be required to understand how data analysis drives decision-making.
Data Scientist salaries have also risen with demand; Data Scientists can typically expect to make six figures. Demand also translates into an ability to relocate far more easily—from city to city, and even internationally.

# Feature Description 

work_year : The year the salary was paid.

experience_level : The experience level in the job during the year with the following possible values: EN Entry-level / Junior MI Mid-level / Intermediate SE Senior-level / Expert EX Executive-level / Director

employment_type : The type of employment for the role: PT Part-time FT Full-time CT Contract FL Freelance

job_title : The role worked in during the year.

salary : The total gross salary amount paid.

salary_currency : The currency of the salary paid as an ISO 4217 currency code.

salaryinusd : The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).

employee_residence : Employee's primary country of residence in during the work year as an
ISO 3166 country code.

remote_ratio : The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%)

company_location : The country of the employer's main office or contracting branch as an ISO 3166 country code.

company_size : The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L more than 250 employees (large)

# The goal of the notebook is to:

1. Explore every feature in the dataset;

2. Work Year Analysis(with Salary, Remote Ratio);

3. Experience Level Analysis (with Employment
Type, Top 3 Job Title, Company Size)

4. Company Location Analysis (with Experience
Level)

5. Salary Analysis (with Work Year, Experience
Level, Company Size, Job Title, Remote Ratio)
