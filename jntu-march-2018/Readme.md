# Refactored@JNTU - Hackathon - March 2018

Welcome to the JNTU Hackathon. Here are the rules:

* You are free to work on as many datasets as you wish within the stipulated time.
* Points shall be given to those notebooks that have enough explanations, exploratory analysis and
results.
* For reference, go through the lessons on Python, Data Science I at  http://www.refactored.ai.
* You shall use only python for all your programming as that is the industry standard. Any other language notebooks
will not be entertained at this point.
* You can work in groups of maximum 4 students.
* Your work shall get submitted as forked repositories to our master repo. 

## Student Group Selection

We shall pick best performing groups amongst the submissions. For reference of best notebooks you can look at:
[Titanic Surviva Prediction](https://github.com/colaberry/refactored_labs/blob/master/Titanic-Revisited.ipynb)

You can also learn what steps you need to take to produce such work at:

1. [Python](https://refactored.ai/path/python/)
2. [Data Science I](https://refactored.ai/path/data-science-I/)
3. [Data Science II(Advanced)](https://refactored.ai/path/data-science-II/)

# Problem Statements

We have 3 problem statements for you. You can choose to work on any or more than one. However, producing a good quality notebook takes time and in our experience, best performing groups have done mostly scored best on solving a single problem with an extensively explained analysis and solution. Here are the 3 problems all of which are equally complex:

## Problem 1: Bitcoin Price Analysis

Historic price of bitcoins are provided for analysis. Your task is to 

1. Ingest the data into a format that is easy for analysis.
2. Perform Exploratory Data Analysis on the dataset.
2. Can you predict the future price of the dataset? 

### 1.1 Time-Series Analysis

Here is an example of time series analysis on Arctic Sea Ice:

[Arctic Sea Ice](https://github.com/colaberry/refactored_labs/blob/master/Arctic_Sea_Ice_Analysis.ipynb)

**Data Description**

* Date : Date of observation
* btc_market_price : Average USD market price across major bitcoin exchanges.
* btc_total_bitcoins : The total number of bitcoins that have already been mined.
* btc_market_cap : The total USD value of bitcoin supply in circulation.
* btc_trade_volume : The total USD value of trading volume on major bitcoin exchanges.
* btc_blocks_size : The total size of all block headers and transactions.
* btc_avg_block_size : The average block size in MB.
* btc_n_orphaned_blocks : The total number of blocks mined but ultimately not attached to the main Bitcoin blockchain.
* btc_n_transactions_per_block : The average number of transactions per block.
* btc_median_confirmation_time : The median time for a transaction to be accepted into a mined block.
* btc_hash_rate : The estimated number of tera hashes per second the Bitcoin network is performing.
* btc_difficulty : A relative measure of how difficult it is to find a new block.
* btc_miners_revenue : Total value of coinbase block rewards and transaction fees paid to miners.
* btc_transaction_fees : The total value of all transaction fees paid to miners.
* btc_cost_per_transaction_percent : miners revenue as percentage of the transaction volume.
* btc_cost_per_transaction : miners revenue divided by the number of transactions.
* btc_n_unique_addresses : The total number of unique addresses used on the Bitcoin blockchain.
* btc_n_transactions : The number of daily confirmed Bitcoin transactions.
* btc_n_transactions_total : Total number of transactions.
* btc_n_transactions_excluding_popular : The total number of Bitcoin transactions, excluding the 100 most popular addresses.
* btc_n_transactions_excluding_chains_longer_than_100 : The total number of Bitcoin transactions per day excluding long transaction chains.
* btc_output_volume : The total value of all transaction outputs per day.
* btc_estimated_transaction_volume : The total estimated value of transactions on the Bitcoin blockchain.





## 2.0 Problem Statement 

### 2.1 Overview of Fraud Detection

Fraud is the event of illegal access or execution of a transaction. Fraud modeling is the process where large amounts of transactional data is analyzed to identify observations which do not generally follow the regular patterns. Due to this nature of the problem, anamoly detection and some classification techniques are most suited to analyze such problems and draw valuable insights. More details are available on [wiki](https://en.wikipedia.org/wiki/Data_analysis_techniques_for_fraud_detection):

### 2.2 Alpha Solutions Fraud Detection

A company Alpha solutions provides fraud detection products, solutions and services to financial businesses. One such financial client has many credit card transactions that are provided as the training data. They want the Financial Data Scientist to build models using the available training data. 

<img src="images/bayesian_network.png", style="width: 400px;">


