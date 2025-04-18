
# A/B Testing Process with Optimum Sample Size Calculation





## Project Objective
This project demonstrates a complete A/B testing workflow with an emphasis on calculating the optimum sample size to ensure statistically valid results. It is designed to help data-driven teams make better decisions by applying proper statistical methods before running experiments.
## 📂 Project Structure

1. #### Sample Size Determination and Power Calculation
For Binomial Distribution
Use Case: Click-Through Rate (CTR) – Clicked/Not Clicked

For Continuous Distribution
Use Case: Daily Active Users (DAU)

2. #### A/B Testing Process
Assignments
Proper random assignment of users into control and test groups

Comparing Group Activity
Comparison of activeness and activity_level between control and variant groups

3. #### Hypothesis Testing
Guardrail Metrics (used to ensure no adverse effects):

By the Activity Level

By the Number of Active Users

Success Metric:

Click Through Rate (CTR)
This is the primary metric for measuring success in the experiment
## 📊 Technologies Used

Python

Pandas – for data manipulation

SciPy / Statsmodels – for statistical calculations and hypothesis testing

Jupyter Notebook – for a clean, interactive coding experience
## 📈 Key Concepts Covered

✅Hypothesis formulation (Null vs. Alternative)

✅Type I and Type II errors

✅Confidence level & statistical power

✅Effect size estimation

✅Sample size calculation using statsmodels

✅Z-test for difference in proportions

✅Interpretation of p-values and confidence intervals
##  How To Use

1. Clone this repository or download the .ipynb notebook.

2. Open the notebook in Jupyter Notebook or Google Colab.

3. Run the cells sequentially to explore the entire A/B testing pipeline.

4. Modify parameters such as effect size, significance level, or power to see how they affect sample size and test results.
## ✅ Ideal For


Data analysts and scientists practicing A/B testing

Growth teams working on conversion rate optimization

Anyone looking to understand how to design statistically sound experiments
## 📊 Visualization: 
### 1 ) Average Daily Click-Through Rate (CTR) Over Time by Group 

![Image](https://github.com/user-attachments/assets/a8142308-7da9-4800-893a-774171ef27ed)
The line chart above illustrates the trend of average daily CTR (avg_daily_ctr) for two groups—control (groupid = 0) and variant (groupid = 1)—over a period of time.

The control group (0) shows a relatively stable CTR throughout the timeline.

The variant group (1) exhibits a noticeable increase in CTR at a specific point, maintaining a higher average afterward.

This suggests that the experiment introduced in the variant group had a positive impact on user engagement, as reflected by the improved click-through rates. The A/B test likely validates that the changes made for group 1 were effective.

### 2) Number of uses based on group 

![Image](https://github.com/user-attachments/assets/343d00be-4fec-41b8-9441-7b2977a2cfaa)


