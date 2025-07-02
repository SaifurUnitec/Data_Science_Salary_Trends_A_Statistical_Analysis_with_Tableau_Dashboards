# Data Science Salary Trends: A Statistical Analysis with Tableau Dashboards

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D1.jpg?raw=true" alt="Image Description" width="600"/>

## Introduction

The salary dataset of the data science industry mainly deals with crucial factors like working years, experience level, employment type, employment resident, remote ratio, company location and company size that influence the salary of employees in the data science industry. It is very significant to identify how factors play a role in determining salaries among employees. 

Dataset Link: https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries/data

By analyzing this dataset and applying data visualization techniques through tableau, my main purpose is to provide insight for taking better organizational strategies to address its problems in the context of primary research question and sub-research questions. 

**Research Questions:** 

What factors have a significant impact on the salary of data science job?

**Sub-Research Questions:**

The following are the sub-research questions that support the main research question’s insight
1)	How experience level and salary in the data science job are correlated?
2)	What are the salary trends based on job titles in various countries? 
3)	How does company size have an impact on salary?

By analyzing sub-research questions and primary research questions, we could identify how the factors determine salary level and what would be the organization’s decision-making strategy to solve the problem.

# Visualisation & Data Analysis

## 1. Data Cleaning

The dataset can be cleaned by removing the index column ‘unnamed: 0’. There is no inconsistency, error and missing value in other columns of the dataset. 

## 2. Relevant Statistics and KPI

To get a better idea about salary trends in data science industries, some KPIs from descriptive statistics derived from Excel are very helpful in interpreting the data. 

### 2.1 Mean Salary by Experience Level: 

**KPI:**  Average salary of each experience level like Entry-level, Mid-level, Senior-level, Executive-level

**Statistics:** 

**•	Entry-level:** Average salary is $61,643.32 USD

**•	Mid-level:** Average salary is $87,996.06 USD

**•	Senior-level:** Average salary is $138,617.29 USD

**•	Executive-level:** Average salary is $ 199,392.03 USD

**Insight:** Salary among employees in the data science industry depends on experiences. The more experience one has, the higher the salary one gets, as executive-level gets the highest salary among the experience level. 

### 2.1 Highest Salary Job Title 

**KPI:** Top three highest average salary job titles. 

**Statistics:**

**•	Machine Learning Scientist:** Mean Salary is $158,412.50 USD

**•	Data Engineer:** Mean Salary is $112,725 USD

**•	Data Scientist:** Mean Salary is $108,187.83

**Insight:** In data science industries, the highest salary is offered to machine learning scientists, data engineers, data scientists because of their specialized knowledge. 

### 2.3 Average Salary by Company Size

**KPI:** Average salary as per the size of the company

**Statistics:**

**•	Lage company (L):** Average salary is $119,242.99

**•	Medium company (M):** Average salary is $116905.46

**•	Small Company (S):** Average salary is $77,632.77

**Insight:** Large companies offer higher salary compared to medium and small companies.

### 2.4 Median and Standard Deviation of the Salary

**KPI:** Median and standard deviation of salary among all categories in the dataset. 

**Statistics:**

**•	Median salary:** The median of all roles is $101,835. USD

**•	Standard Deviation:** Standard deviation is $71,003.59 USD

**Insight:** Median salary indicates that half of the salary is below the median salary and half is the above of it.  Standard deviation indicates that how much salary deviates from the mean salary. 

## 3. Visualization Outputs

I used Tableau to find out the answer to the research question by creating several visualizations.

**Bar Chart and Box Plot:** Both bar chart and box plot have been used to identify how experience level influences salary in data science industries.

**Geographical Map and Heat map:** To compare average salary in different job titles across the different regions.

**Dual Combination Chart and Line Chart:** Showing average salary based on company size over the year.

# Investigations and Findings

## 1.	Experience Level and Salary Distribution

**•	Bar Chart**

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D2.jpg?raw=true" alt="Image Description" width="600"/>

**•	Box Plot**

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D3.jpg?raw=true" alt="Image Description" width="600"/>

-	The bar chart and box plot present how experience level and salary in data science jobs are correlated which supports sub-research question 1.

-	It is clear from both bar chart and box plot that salary distribution of data science job depends on experience level. Executive level experienced people have got the highest gross salary among other experienced groups which is more than USD 170K. Executive level also has fewer outliner compared to other experienced level people. Here, salary trend and experience level are positively correlated.

## 2.	Salary Trends Based on Job Titles in Various Regions

**•	Geographical Map**

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D4.jpg?raw=true" alt="Image Description" width="600"/>

**•	Heatmap**

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D5.jpg?raw=true" alt="Image Description" width="600"/>

-	Geographical Map and Heatmap show how the salary of data science jobs vary by different regions and job titles which support sub-research question 2. 

-	The map indicates median salaries for data science jobs across the different countries. Russia and the US pay the highest median salary, with $157,500 and $135,000 respectively, while Iran pays the lowest median salary at $4,000.

-	The heatmap presents a Data Analytics Lead in the US gets the highest median salary at $405,000, while a Data Scientist in Mexico gets the lowest at $2,859.

## 3.	Company Size and Salary Distribution

**•	Line Chart**

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D6.jpg?raw=true" alt="Image Description" width="600"/>

**•	Dual Combination Chart**

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D7.jpg?raw=true" alt="Image Description" width="600"/>

-	Line chart and dual combination chart show how company size has an impact on the median salary of data scientist job that support sub-research question-3 

-	Charts show that salary of large companies continuously increased from 2020 to 2022. Medium companies' salaries fluctuated each year, with the highest in 2022 but the lowest in 2021. Small companies paid the lowest salaries, except in 2021.

## Dashboard-1 (Supported by Sub- Research Question-1)

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D8.jpg?raw=true" alt="Image Description" width="600"/>

## Dashboard-2 (Supported by Sub- Research Question-2)

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D9.jpg?raw=true" alt="Image Description" width="600"/>

## Dashboard-3 (Supported by Sub- Research Question-3)

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D10.jpg?raw=true" alt="Image Description" width="600"/>

## Story

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D11.jpg?raw=true" alt="Image Description" width="600"/>

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D12.jpg?raw=true" alt="Image Description" width="600"/>

<img src="https://github.com/SaifurUnitec/Data_Science_Salary_Trends_A_Statistical_Analysis_with_Tableau_Dashboards/blob/my-new-branch/D13.jpg?raw=true" alt="Image Description" width="600"/>
