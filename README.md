# mini-project-III
Customer segmentation analysis using financial data.


### Topics
This mini project is dedicated to following topics:
- Data Wrangling
- Data Visualization
- Data Preparation and Feature Engineering
- Dimensionality Reduction
- Unsupervised Learning

### Data
We will be using old data about different financial transactions. You can download the data from [here](https://drive.google.com/file/d/1zAjnf936aHkwVCq_BmA47p4lpRjyRzMf/view?usp=sharing). The data contains following tables:

- twm_customer - information about customers
- twm_accounts - information about accounts
- twm_checking_accounts - information about checking accounts (subset of twm_accounts)
- twm_credit_accounts - information about credit accounts (subset of twm_accounts)
- twm_savings_accounts - information about savings accounts (subset of twm_accounts)
- twm_transactions - information about financial transactions
- twm_savings_tran - information about savings transactions (subset of twm_transactions)
- twm_checking_tran - information about checking transactions (subset of twm_transactions)
- twm_credit_tran - information about credit transactions (subset of twm_transactions)


### Output

This miniproject was the result of a group effort in which we:

1.  create two separate customer segmentations (using clustering) to split them into 3-5 clusters: 
    - based on demographics (only on the information from twm_customer)
    - based on their banking behavior

2. visualize the created clusters using [radar charts](https://plotly.com/python/radar-chart/) and compare them against each other

3. visualize segmentations using scatter plot. We will have to use PCA to be able to plot our observations in 2D.
