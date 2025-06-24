# Bitcoin Wallet Transaction Analysis

This is a sample project demonstrating on-chain analysis of a Bitcoin wallet using publicly available data from [Blockchair](https://blockchair.com/).

## 🔍 Target Wallet

- **Wallet Address:** `34xp4vRoCGJym3xR7yCVPFHoCNxv4Twseo`
- **Wallet Type:** Likely a cold wallet (commonly associated with exchange reserves)
- **Analysis Period:** May 1, 2025 – May 30, 2025
- **Number of Transactions:** 5 incoming transactions

## 📊 Methodology

1. Retrieved the wallet statement PDF from Blockchair covering the specified time period.
2. Extracted the following details from each transaction:
   - Timestamp
   - Transaction ID
   - Sender and receiver addresses
   - Amount (in BTC and USD)
   - Transaction fee
3. Structured the data into a Google Spreadsheet for clarity and future reference.
4. Reviewed each transaction individually and added key observations.

## 📁 Files

- `transactions.csv`: Cleaned and structured transaction data
- `wallet-analysis.pdf`: Original wallet statement from Blockchair

## 💡 Key Observations

- All transactions were **incoming only**, suggesting this is a **receiving address** (not used for sending).
- The wallet received multiple small amounts (under 0.0001 BTC), possibly test deposits or dusting transactions.
- All incoming funds came from different sender addresses.
- The same receiving address (`34xp4v...`) appeared consistently in multi-output transactions.

## 📚 Tools Used

- [Blockchair Bitcoin Explorer](https://blockchair.com/bitcoin)
- Google Sheets

## 🧠 Skills Demonstrated

- On-chain blockchain data analysis
- Transaction flow tracing
- Data structuring and reporting
- Familiarity with common blockchain explorers

## 📨 Contact

Feel free to contact me if you would like a similar analysis or if you have any questions regarding this project.
