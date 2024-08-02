Loan Risk Detection Project
 
 

Table of Contents
Overview
Data Dictionary
Data Pre-processing
Initial Data Exploration
Model Building and Additional Data Treatments
Final Model
Overview
History of Loan Risk
Loan risk has been a challenge since the inception of banking, evolving from personal trust-based assessments to complex, data-driven models. Initially reliant on personal relationships, modern risk assessment now utilizes advanced algorithms and vast datasets to predict defaults more accurately.

Industry Background and Key Objectives
Banks provide critical financial support but face significant risks when borrowers default. Efficient risk detection systems are essential to mitigate these risks, ensuring financial stability and compliance with regulatory requirements.

Data Dictionary
Key Attributes
id: Unique identifier for each loan.
member_id: Identifier for the borrower.
loan_amnt: Amount of the loan applied for.
funded_amnt: Amount sanctioned.
term: Loan term in months (36 or 60).
int_rate: Interest rate on the loan.
installment: Monthly payment.
grade: Loan grade assigned by the lender.
sub_grade: Loan sub-grade.
emp_title: Borrower's job title.
emp_length: Employment length in years (0-10).
home_ownership: Home ownership status.
annual_inc: Self-reported annual income.
verification_status: Income verification status.
issue_d: Month loan was funded.
loan_status: Current status of the loan.
purpose: Purpose of the loan.
dti: Debt-to-income ratio.
delinq_2yrs: Delinquencies in the past 2 years.
earliest_cr_line: Date of the borrower's earliest credit line.
inq_last_6mths: Loan inquiries in the last 6 months.
mths_since_last_delinq: Months since last delinquency.
open_acc: Number of open credit lines.
pub_rec: Number of derogatory public records.
revol_bal: Total credit revolving balance.
revol_util: Revolving line utilization rate.
total_acc: Total number of credit lines.
initial_list_status: Initial listing status of the loan.
out_prncp: Remaining outstanding principal.
total_pymnt: Payments received to date.
total_rec_prncp: Principal received to date.
total_rec_int: Interest received to date.
total_rec_late_fee: Late fees received to date.
recoveries: Total recovery procedures.
collection_recovery_fee: Fees collected during recovery.
last_pymnt_d: Last payment date.
last_pymnt_amnt: Last payment amount received.
next_pymnt_d: Next scheduled payment date.
last_credit_pull_d: Most recent credit pull date.
collections_12_mths_ex_med: Collections in the last 12 months excluding medical collections.
mths_since_last_major_derog: Months since last major derogatory event.
application_type: Individual or joint application.
annual_inc_joint: Combined annual income for co-borrowers.
dti_joint: Debt-to-income ratio for co-borrowers.
acc_now_delinq: Number of accounts currently delinquent.
tot_coll_amt: Total collection amounts owed.
tot_cur_bal: Total current balance of all accounts.
total_rev_hi_lim: Total high credit/credit limit.
Data Pre-processing
Steps Involved
Reading Data: Import the CSV file and assess its size and structure.
Handling Missing Values: Impute missing values to ensure data completeness.
Data Cleaning: Rectify grammatical errors and make cosmetic improvements.
Data Transformation: Scale and encode data for uniformity.
Outlier Treatment: Identify and treat outliers to avoid skewed results.
Balancing Data: Address imbalances in the dataset for better model performance.
Interpretation
The dataset includes 17 float, 15 int, and 17 object values.
Dropped columns with high missing values or irrelevant data.
Initial Data Exploration
Analysis Techniques
Univariate Analysis: Examine each variable individually.
Bi-variate Analysis: Analyze relationships between two variables.
Multi-Variate Analysis: Explore complex interactions among multiple variables.
Objectives
Identify patterns and correlations.
Gain insights into the data distribution.
Detect anomalies and trends.
Model Building and Additional Data Treatments
Approach
Data Collection: Gather relevant data from various sources.
Feature Engineering: Select and create relevant features.
Model Development: Use machine learning algorithms to build predictive models.
Model Evaluation: Assess model performance using metrics like accuracy, precision, recall, and F1-score.
Model Deployment: Integrate the model into the production environment.
Model Monitoring and Maintenance: Continuously monitor and update the model as needed.
Techniques Used
Splitting data into training and test sets.
Scaling and encoding data for consistency.
Training various classification models.
Evaluating model performance and making adjustments.
Final Model
Summary
The final model aims to accurately predict loan defaults.
Utilizes advanced machine learning techniques.
Provides actionable insights for risk management.
Benefits
Improved credit decision-making.
Enhanced early warning systems.
Proactive risk mitigation strategies.
Optimized loan pricing and terms.
Compliance with regulatory requirements
