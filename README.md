# ETL

# ETL – Extract, Transform, and Load data.

First, the following four data files (Excel files) had been extracted from https://www.kaggle.com/datasets and put under the directory of “Resources”:

"bitcoin_price",
"ethereum_price",
"IBM",
"MSFT"

They are Excel files. 


Secondly, These data files were transformed onto Python Pandas dataframes and named as following:
"new_bitcoin_df" 
"new_ethereum_df"
"new_IBM_df"
"new_MSFT_df"



Third, These transformed files were Loaded onto MySQL server under database "Proj2_db" and stored in four tables:
"bitcoin"
"ethereum"
"ibm "
"msft"


After that, I made two sql queries: 

The first query is to select and join the bitcoin table and Ethereum table and plot the prices so users can see the comparison of the bitcoin price and the Ethereum price; 

The second query is to select and join the ibm table and msft table and plot the pirces so users can see the comparison of the ibm price and the msft price.  

The two plots are saved with names of "bitcoin_vs_ethereum.png" and "ibm_vs_msft.png" under the directory of "Images".



Note: the python file which does the transforming and loading data steps is named "stock-vs-coins"  and is saved under directory of "Solved".
