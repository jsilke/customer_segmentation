# Customer Segmentation ![Issues](https://img.shields.io/github/issues/jsilke/customer_segmentation) ![Last Commit](https://img.shields.io/github/last-commit/jsilke/customer_segmentation) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## Contributors

- Jonas Bacareza [![GitHub](https://img.shields.io/github/followers/jebacareza?style=social)](https://github.com/jebacareza)
- Dylan Wu [![GitHub](https://img.shields.io/github/followers/DylanFWu?style=social)](https://github.com/DylanFWu)
- Jordan Silke [![GitHub](https://img.shields.io/github/followers/jsilke?style=social)](https://github.com/jsilke)

### Data Source & Description

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

### Summary

This project was the result of a group effort in which we:

1.  created two separate segmentation analyses (using clustering) to split customers into 3-5 clusters using: 
    - [demographics](./demographics.ipynb) (only information from twm_customer)
    - [all information](./full_analysis.ipynb) (twm_customer, twm_accounts, and twm_transactions)

2. visualized the created clusters using [radar charts](https://plotly.com/python/radar-chart/) and compared them against each other.

3. visualized segments using PCA to plot our observations in 2D.

### Structure

```bash
.
│   .gitignore
│   README.md
│   demographics.ipynb      # Analysis of twm_customer
│   full_analysis.ipynb     # Analysis of all tables
│   gower_modelling.ipynb   # Transformation and visualization of all data.
```