🚨 Bank Transaction Dataset for Fraud Detection – Power BI Report  
This project analyzes suspicious activity in a large bank transaction dataset. Using a combination of PostgreSQL and Power BI, it identifies potential fraud based on balance anomalies, device and IP changes, and post-debit balance increases.

The objective was to detect subtle patterns of fraudulent behavior and recommend improvements to monitoring and controls.

📄 Report Contents  
The report includes the following dashboards:

- **Expected Balance Deviations**: Highlights 821 transactions with balance gaps totaling over $3.7M. The top 10 accounts have consistent discrepancies over $20K.
- **Device and IP Changes**: Tracks five device and IP change events that occurred in rapid succession, suggesting possible account misuse.
- **Balance Increases After Debits**: Identifies 821 debit transactions where balances increased instead of decreasing — a likely fraud pattern or system fault.
- **Anomaly Summary**: Consolidates all anomalies into a risk profile. Top-risk account (AC00304) recorded 12 anomalies. 406 unique accounts were affected in total.

💡 Key Insights

- Most anomalies are concentrated in a small set of accounts.
- IP and device shifts often occurred simultaneously, raising security concerns.
- Increases in account balance after debits suggest manipulation or technical flaws.
- $252K worth of transactions were flagged as suspicious.

🔧 Tools Used

- PostgreSQL + Table Plus (data cleaning and querying)  
- Microsoft Power BI (data visualization)  
- Excel (supporting calculations and export)

📥 Report  
[📄 Download the Fraud Detection Report PDF](#) *(link to be added)*

Created using Power BI, PostgreSQL, and publicly available transaction data from Kaggle.  
© 2025 Lajos Almási

[lajos_portfolio/bank_fraud_detection at main · lajosalmasi/lajos_portfolio](https://github.com/lajosalmasi/lajos_portfolio)
