**Goal:** 
The goal of the project is to evaluate the results of four A/B tests, assess the significance of the results and provide recommendations based on them.


**Conclusions:**
General conclusions and recommendations are drawn on the basis of results with proven statistical significance. Assuming that the test was carried out over a sufficient period of time and achieved the expected sample size.

  ***Test 1:***
  The test showed an increase in add_payment_info by 12%, add_shipping_info by 6%, and begin_checkout by 6%. However, the metrics new_accounts and session_with_orders did not show statistically significant changes. Recommendations: check the distribution uniformity between segments to determine whether the changes have an impact on increasing the number of orders.

***Test 2:***
The test showed a 9% increase in add_to_cart and a 23% increase in clicks. This indicates that the test is successful in engaging users; however, it has not been proven that this leads to an increase in purchases and conversion. Recommendations: Check user segmentation and whether only certain segments had statistically significant changes in further funnel steps. If these changes are not found, reject the test, as it did not bring practical benefits.

***Test 3:***
The test showed a 3% decrease in add_to_cart and begin_checkout. Recommendations: Reject the changes as they showed negative results for conversion at intermediate funnel stages.

***Test 4:***
The test showed a decrease in begin_checkout by 2% and new_account by 3%. Recommendation: Reject the changes, as they lead to a significant decrease in account creation conversion.
(Note: all said percentages are relative.)

<img width="991" height="651" alt="image" src="https://github.com/user-attachments/assets/c368f7ac-b6e7-43f0-b10b-e848ce6b7a34" />

**Link to Dashboard:** https://public.tableau.com/views/AudienceBehaviorSalesPerformance/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**Tech Stack:**
SQL (BigQuery) – data extraction.
Python (Pandas, Statsmodels) – calculations and creating dataframes for analysis..
Tableau – data visualization.

**Project Workflow:**
1. Data extraction using SQL and BigQuery.
2. Calculating number of entries, conversion rates and statistical significance for each test  in total and segments section.
3.Results visualization.

