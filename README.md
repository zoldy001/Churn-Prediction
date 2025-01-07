# Churn-Prediction

In this project, we will explore and analyze a dataset of telecommunication company's costumers in depth, with the goal of identifying patterns and correlations between various customer attributes and their likelihood of churning.

Customer churn prediction is a critical business problem faced by companies in many industries, particularly those offering subscription-based services. Identifying customers likely to churn allows businesses to proactively implement retention strategies, improving customer loyalty and boosting long-term profitability.

## Exploratory Data Analysis (EDA)

### Key takeaways:

Demographics Churn:

- No significant gender bias in churn behavior is observed
- Senior citizens show a notably higher churn rate proportionally
- Customers with partners (1) show significantly lower churn rates (~20%) than those without partners (0) (~35%)
- The churn rate for customers with dependents is approximately 20%, compared to ~35% for those without


Numerical Churn:

- Distinct Pricing Tiers are visible in the distribution:

- Non-churning customers (green) show a multi-modal distribution with peaks at 20, 50, and 80

- There might be a price sensitivity threshold around $70 where churn risk increases significantly
<img src="./img/img_1.png" alt="Local Image" style="width:70%; height:auto;">


* Churn decreases with tenure, most costumers churn early
* Costumers with low monthly charges have low churn regardless of tenure
<img src="./img/img_2.png" alt="Local Image" style="width:70%; height:auto;">
