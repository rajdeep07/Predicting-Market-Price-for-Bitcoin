# Predicting-Market-Price-for-Bitcoin
Predicting Market Price for Bitcoin using regressors like KNN repressor, linear regression, Ridge, Lasso, polynomial regression, SVM 
The explanation of the data set : Bitcoin Dataset (bitcoin_dataset.csv) :

This dataset has the following features.

    Date : Date of observation
    btc_market_price : Average USD market price across major bitcoin exchanges.
    btc_total_bitcoins : The total number of bitcoins that have already been mined.
    btc_market_cap : The total USD value of bitcoin supply in circulation.
    btc_trade_volume : The total USD value of trading volume on major bitcoin exchanges.
    btc_blocks_size : The total size of all block headers and transactions.
    btc_avg_block_size : The average block size in MB.
    btc_n_orphaned_blocks : The total number of blocks mined but ultimately not attached to the main Bitcoin blockchain.
    btc_n_transactions_per_block : The average number of transactions per block.
    btc_median_confirmation_time : The median time for a transaction to be accepted into a mined block.
    btc_hash_rate : The estimated number of tera hashes per second the Bitcoin network is performing.
    btc_difficulty : A relative measure of how difficult it is to find a new block.
    btc_miners_revenue : Total value of coinbase block rewards and transaction fees paid to miners.
    btc_transaction_fees : The total value of all transaction fees paid to miners.
    btc_cost_per_transaction_percent : miners revenue as percentage of the transaction volume.
    btc_cost_per_transaction : miners revenue divided by the number of transactions.
    btc_n_unique_addresses : The total number of unique addresses used on the Bitcoin blockchain.
    btc_n_transactions : The number of daily confirmed Bitcoin transactions.
    btc_n_transactions_total : Total number of transactions.
    btc_n_transactions_excluding_popular : The total number of Bitcoin transactions, excluding the 100 most popular addresses.
    btc_n_transactions_excluding_chains_longer_than_100 : The total number of Bitcoin transactions per day excluding long transaction chains.
    btc_output_volume : The total value of all transaction outputs per day.
    btc_estimated_transaction_volume : The total estimated value of transactions on the Bitcoin blockchain.
    btc_estimated_transaction_volume_usd : The estimated transaction value in USD value.

NOTES :

    Blocks are files where data pertaining to the Bitcoin network is permanently recorded. A block records some or all of the most recent Bitcoin transactions that have not yet entered any prior blocks. Thus a block is like a page of a ledger or record book.

https://www.youtube.com/watch?v=Lx9zgZCMqXE

Project description:

    1. Read data into Jupyter notebook, use pandas to import data into a data frame
    2. Preprocess data: explore data, address missing data, categorical data and data scaling. Justification of the type of scaling used
    3. Train your dataset using all the linear regression models. Used Grid Search to find the best scaling parameter. Used plots and graphs to help you get a better glimpse of the results.
    4. Then use cross validation to find average training and testing score.
    5. Following regression models: KNN repressor, linear regression, Ridge, Lasso, polynomial regression, SVM both simple and with kernels have been applied. 
    6. Finally predict the market price for the test_set.
