# Data-engineering-ETL-project

This project focuses on extracting data from the JSON file "bank_market_cap.json," transforming the market cap currency using exchange rate data, and loading the transformed data into a separate CSV file.

Overview:
The ETL process consists of three main steps:
Extract- Data is extracted from the JSON file "bank_market_cap.json," which contains bank and market cap information.
Transform- The extracted data includes market cap values in different currencies. To ensure consistency, the market cap currency will be transformed using exchange rate data. The transformed data will have a unified currency for easy comparison and analysis.
Load- The transformed data will be loaded into a separate CSV file, making it easily accessible for further analysis or integration with other systems.
