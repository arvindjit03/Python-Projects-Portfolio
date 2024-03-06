This project shows EDA and Statistical Analysis of Data professionals in AI and Data science space. 

We have used a Kaggle dataset containing weekly updated data regarding the Data jobs and salaries for each profession. [Dataset](https://www.kaggle.com/datasets/lorenzovzquez/data-jobs-salaries/data?select=salaries.csv)

There are 11 attributes present in the dataset. The description for each is as follows:

**work_year**: The year the salary was paid.

**experience_level**: The experience level in the job during the year with the following possible values:

- EN: Entry-level / Junior

- MI: Mid-level / Intermediate

- SE: Senior-level / Expert

- EX: Executive-level / Director

**employment_type**: The type of employment for the role:
- PT: Part-time
- FT: Full-time
- CT: Contract
- FL: Freelance

**job_title**: The role worked in during the year.

**salary**: The total gross salary amount paid.

**salary_currency**: The currency of the salary paid as an ISO 4217 currency code.

**salary_in_usd**: The salary in USD (FX rate divided by avg. USD rate of the respective year via data from fxdata.foorilla.com).

**employee_residence**: Employee's primary country of residence as an ISO 3166 country code during the work year.

**remote_ratio**: The overall amount of work done remotely, possible values are as follows:

- 0: No remote work (less than 20%)

- 50: Partially remote/hybrid
  
- 100: Fully remote (more than 80%)

**company_location**: The country of the employer's main office or contracting branch as an ISO 3166 country code.

**company_size**: The average number of people that worked for the company during the year:

- S: less than 50 employees (small)

- M: 50 to 250 employees (medium)

- L: more than 250 employees (large)
