# Stock Data Extraction Challenge
This project is a data engineering challenge that focuses on extracting, analyzing, and storing stock market data from the past 30 working days for five major stock tickers: ITUB (Itaú), BBD (Bradesco), MSFT (Microsoft), GOOG (Google), and TSLA (Tesla). We use the Alpha Vantage API to fetch the stock market data and perform various data manipulation and statistical analysis tasks using Python, Pandas, and Numpy libraries. The project is also integrated with a PostgreSQL database for storing the extracted data.

# Features
Extract the 30-work day daily data for the selected stock tickers.
Calculate various statistical values for the last 30 work days, such as mean, standard deviation, minimum value, quartile distribution, and maximum value.
Sort and select the n highest and n-lowest volume days from the last 30 work days.
Calculate the sum of ITUB and BBD volumes from the last 30 work days.
Export the data to a CSV file and import it into a PostgreSQL database.

# Requirements
Python 3.7+
Alpha Vantage API key
Pandas library
Numpy library
Psycopg2 library (for PostgreSQL integration)
An active PostgreSQL database

# Usage
1. Clone the repository and navigate to the project directory.

2. Install the required libraries:

```
pip install pandas numpy psycopg2-binary

``` 

3. Replace the chave_api variable with your own Alpha Vantage API key in the chave_api.py file.

4. Update the PostgreSQL database credentials in the db_name, db_user, db_password, db_host, and db_port variables.

5. Run the main Python script to execute the data engineering challenge:


The script will extract the stock market data, perform the required analysis tasks, and store the data in a PostgreSQL database.

# License
This project is licensed under the MIT License.