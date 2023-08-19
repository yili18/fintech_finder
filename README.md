# Fintech Finder Application Payment

## The project is to integratie the Ethereum blockchain network into the Fintech Finder application in order to enable our customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

### Step 1: Import Ethereum Transaction Functions into the Fintech Finder Application
* Add our mnemonic seed phrase (provided by Ganache) to the starter code’s `.env` file
* Import the three functions from the `crypto_wallet.py` file to `fintech_finder.py` file: `generate_account`, `get_balance`, `send_transaction`

### Step 2: Sign and Execute a Payment Transaction
* Calculate a fintech professional’s `wage`: the candidate’s hourly rate multiply `hours` variable
* Call the `send_transaction` function and pass it three parameters: `account`, `candidate_address`, `wage`
* Save the transaction hash that the `send_transaction` function returns as a variable named `transaction_hash`

### Step 3: Inspect the Transaction
* Launch the Streamlit application by typing `streamlit run fintech_finder.py`
* Test on the resulting webpage:
  - Select a candidate that we would like to hire from the appropriate drop-down menu
  - Enter the number of hours that you would like to hire them for
  - Success!

![Screenshot 1](success.PNG)

![Screenshot 2](https://github.com/yili18/fintech_finder/blob/main/address%20balance.PNG)  

![Screenshot 3](https://github.com/yili18/fintech_finder/blob/main/transaction%20details.PNG) 

![Screenshot 4](https://github.com/yili18/fintech_finder/blob/main/recipient%E2%80%99s%20address%20balance%20and%20history.PNG)
