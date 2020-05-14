# yahoo_finance_data_scrape
Python application that allows you to pass a stock ticker and receive an XLSX output of the company Summary, Profile, Income Statement, Balance Sheet, and Cash Flow data.

The data is scraped from:

[Yahoo Finance Website](https://finance.yahoo.com/)

## Installation

Clone this repository using the "Clone or download" button in the top right corner of the repository or by typing the git clone command:

```bash
git clone https://github.com/tcharts-boop/yahoo_finance_data_scrape.git
```
or for a specific directory:

```bash
git clone https://github.com/tcharts-boop/yahoo_finance_data_scrape.git /specific/directory/
```

After the repository is cloned, navigate to the directory of the cloned repository and install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

To run from the command prompt, you must be in the directory of the cloned repository.

From there you can run by typing:
```bash
python yfinance_scraper.py
```

The script will ask for a stock ticker (the abbreviated stock name for the company).

After inputting the stock ticker, the script will scrape the data and write it to a .xlsx file and store it in the output directory with the stock symbol as part of the naming convention.

Directory:

```bash
./yahoo_finance_data_scrape/output 
```

The workbook will contain five sheets: Summary, Profile, Income_Statement, Balance_Sheet, and Cash_Flow.

## Author

[Theodore Charts](https://www.linkedin.com/in/tedcharts/)

## License
[MIT](https://choosealicense.com/licenses/mit/)

