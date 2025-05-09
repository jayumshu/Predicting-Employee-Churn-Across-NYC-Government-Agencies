# Predicting Employee Churn Across NYC Government Agencies
 Machine Learning (Spring 2025) Final Project - James Hu
Please note: Full report under Final Project Report_James Hu (1) [12 pages]
The research question I’m aiming to answer is can we predict whether a civil-servant will stay on the payroll next year (t+1) with reasonable accuracy (greater than 80%), given information we have about their seniority, agency, salary, and other engineered features at the end of this year (t). The intended audience for my research are the agency managers of the aforementioned departments who need to decide A) approximately how many new hires they will have to account for time and budget wise and B) who to give extra bonuses to in order to incentivize their retention. I use a Random Forest model to predict churn, using the following metrics in evaluation: Accuracy (total % of employees predicted correctly), Precision, and Recall (evaluates how good the model is at actually identifying all churned employees). I compare against a baseline model that randomly guesses churn using knowledge of the underlying proportion of retained:churned employees in each training set. The key finding I obtained from my final Random Forest model that uses 2015-2023 data in its training set, and predicts on feature data from 2024 suggests the following estimates for employee churn in 2024:
A. Overall percent to churn in 2024 across the 3 major agencies : 30.2%
B. Department of Parks and Recreation: 64.3%
C. Department of Sanitation: 10.6%
D. Department of Correction: 6.0%

# Project Overview
https://data.cityofnewyork.us/City-Government/Citywide-Payroll-Data-Fiscal-Year-/k397-673e/about_data
Visit this link, create app token, and query data using Loading Data and Packages with your unique app token and login credentials

# Project Structure
For reproducibility, please run .Rmd files in the following order 
Loading Data and Packages.Rmd
Data Cleaning and Exploration.Rmd
Feature Distributions (Unprocessed).Rmd
Feature Selection and Engineering.Rmd
Modeling and Evaluation.Rmd
