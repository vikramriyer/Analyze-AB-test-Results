# Analyze-AB-test-Results

## Administrative stuff
Please download/save and view the [Analyze_ab_test_results_notebook.html](https://github.com/vikramriyer/Analyze-AB-test-Results/blob/master/Analyze_ab_test_results_notebook.html) file to see the entire report written using Jupyter Notebook which has all the code as well.

## Summary
This is an A/B testing assignment completed for Udacity's Data Analyst Nano Degree Program. The project consisted of understanding the results of an A/B test run by an e-commerce website and helping the company understand through statistical conclusions, if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Objectives
- practice working on A/B testing projects and their practical difficulties
- perform A/B tests and make recommendations backed by computed inferences

## Project Steps & Research Questions:
### Data Wrangling:
- remove duplicates or records with missing or mismatched values
- handle the rows where the landing_page and group columns don't align

### Data Analytics:
- Compute probabilities of converting:
  - regardless of page.
  - Given that an individual received the treatment
  - Given that an individual received the control page
- Perform Hypothesis Testing and calculate p-values
- Conduct Logistic Regression 
