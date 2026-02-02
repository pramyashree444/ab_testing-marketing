# ab_testing-marketing
ab-testing_marketing_campaign
Task 11: A/B Testing – Hypothesis Testing in Python

 Project Overview

This project performs A/B testing on a marketing dataset to evaluate whether an advertisement campaign (Ad group) leads to a significantly different conversion rate compared to a public service announcement (PSA group).

The analysis is done using Python in Google Colab with statistical hypothesis testing to support data-driven business decisions.


---

🛠 Tools & Libraries

Google Colab

Python

pandas

numpy

scipy

matplotlib

---
 Dataset

Marketing A/B Testing Dataset

Key Columns Used:

test group → Experiment groups (psa = control, ad = test)

converted → Conversion outcome (True/False)

---

Methodology

1. Loaded and explored the dataset

2. Identified control (PSA) and test (Ad) groups

3. Defined hypotheses:

H0: No significant difference in conversion rates

H1: Significant difference in conversion rates

4. Set significance level α = 0.05

5. Calculated conversion rates for both groups

6. Applied Chi-Square Test for hypothesis testing

7. Interpreted p-value and confidence interval

8. Visualized conversion rate comparison

9. Generated business recommendation

---

 Statistical Test

Test Used: Chi-Square Test of Independence

Reason: Conversion data is categorical (Yes/No)

---

 Results

The p-value obtained was extremely small (<< 0.05)

Null hypothesis was rejected

A statistically significant difference exists between PSA and Ad groups

---

 Business Recommendation

Based on statistical evidence, the advertisement campaign shows a meaningful impact on user conversion. It is recommended to roll out the Ad campaign.

---
 Deliverables

task11_abtest.ipynb – Complete analysis notebook

ab_test_summary.csv – Summary of conversion rates

final_recommendation.txt – Business recommendation

README.md – Project documentation

 Key Learning Outcome

Ability to perform A/B testing, interpret statistical significance, and make data-driven business recommendations.
