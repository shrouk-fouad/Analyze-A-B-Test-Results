# Analyze-A-B-Test-Results
Project to analyze A/B test results using python

##  Overview 
For this project, I worked to get the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. The goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Built With
* Pandas
* Numpy
* Random
* Matplotlib
* Statsmodels

## Findings
1. P-value for countries is higher than .05, hence countries have no significant influence on conversion rates.
2. P-value for interactions is higher than .05, which suggests that there is no significant influence of landing pages in the US and Canada on conversion rates.
3. The results of this test suggest that the new page doesn't have a higher conversion rate than the old page, so the company shouldn't implement the new page.
