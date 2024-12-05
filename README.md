# Financial Analysis Project

This project is designed to analyze financial statements and ratios for a company. The following Python scripts are included:

1. **financial-scraper.py**: Scrapes financial data from MoneyControl.com and saves it in an Excel file.
2. **financial-solven-ratio.py**: Calculates solvency ratios based on the scraped financial data.
3. **financial-profit-Ratio.py**: Calculates profitability ratios based on the scraped financial data.
4. **financial-liquidity-Ratio.py**: Calculates liquidity ratios based on the scraped financial data.

## Project Structure

- `README.md`: This file
- `Financial_Statement.xlsx`: The Excel file containing the scraped financial statements.
- `Financial_Ratio.xlsx`: The Excel file containing calculated financial ratios.

## Usage

1. Run `financial-scraper.py` to scrape financial data from MoneyControl.com and save it in `Financial_Statement.xlsx`.
2. Run `financial-solven-ratio.py`, `financial-profit-Ratio.py`, and `financial-liquidity-Ratio.py` to calculate the respective financial ratios and save them in `Financial_Ratio.xlsx`.

## Dependencies

- pandas
- numpy
- openpyxl
- xlsxwriter
- requests
- beautifulsoup4

To install the dependencies, run:

```sh
pip install pandas numpy openpyxl xlsxwriter requests beautifulsoup4
```

## Contributing

Feel free to contribute to this project by adding new features or improving existing ones. Make sure to follow the coding standards and best practices.
