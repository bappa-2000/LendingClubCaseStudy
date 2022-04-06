# Lending Club Case Study
> The goal of this case study is to help finance company in decision making for loan approval based on the applicant’s profile


## Table of Contents
* [Business Requirements](#business_requirements)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Python Libraries Used](#python-libraries-used)
* [Conclusions](#conclusions)


## Business Requirements
- Identify patterns using past loan application data that can trigger charge-off loans
- Risks involved
  - Not approving loans for the applicants who are likely to repay the loan
  - Approving loans for the applicants who are likely to default
- A dataset of loan applications from 2007 to 2011 has to be referred as the base for this analysis


## Approach
- Data fields understanding
- Data Pre-processing
- Exploratory Data Analysis 


## Technologies Used
- Python 3.8
- Jupyter Notebook


## Python Libraries Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Plotly, Express, Graph Objects, Subplot


## Conclusions
- Applicants who have taken the loan for “small business” are having highest probability (27.79%)  to default. 
- Defaulter Probability is the highest (22.15%) for the applicants having no employment history  (Marked as “Unknown” in the graph)
- Probability to default is increasing from grade A to G. Sub-grade F5 has maximum probability (52.5%) to default.
- Low annual income ($25,000 or less) applicants are highest probable (19.59%) to default. 
- Probability to default is increasing with increase in Loan Amount. Applicants with Loan amount of $25,000 or above are highly probable to default. 
- Probability to default is increasing with increasing Interest Rate and DTI. Loan applicants with interest rate or DTI 19% or above are highly probable to default.
- Applicants from Nebraska (NE) have the highest probability (60%) to default.
