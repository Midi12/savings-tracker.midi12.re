# Savings Balance Tracker

This is a simple, client-side web application for tracking your savings and investment balances over time. It allows you to visualize your financial accounts, filter by date and account, and see your total balance in a unified currency.

## Features

- **Visualize Your Balances:** Upload a CSV file with your account balances and see them plotted on an interactive chart.
- **Multi-Currency Support:** Provide an optional currency conversion file to see all your balances converted to a single currency (e.g., EUR).
- **Interactive Filtering:** Filter the data by account and date range to focus on specific periods or assets.
- **Data Table:** View your raw data in a sortable and color-coded table.
- **Client-Side Processing:** All data is processed in your browser. No data is ever uploaded to a server.
- **Dark/Light Mode:** Switch between themes for comfortable viewing.

## How to Use

1.  Open `index.html` in your web browser.
2.  Click "Choose Balance CSV File" and select your balance data file.
3.  (Optional) Click "Choose Currency CSV File" and select your currency conversion rates file.
4.  Use the filter controls to explore your data.

For detailed information on the required CSV formats, please see the [documentation page](documentation.html).

## CSV File Formats

This tool requires specific CSV formats to work correctly. Please refer to the [documentation](documentation.html) for detailed instructions.

- **Balance CSV:** Must contain `Account name`, `date`, `balance`, and `currency` columns, separated by semicolons.
- **Currency CSV:** Must contain `from`, `to`, and `rate` columns, separated by semicolons.

You can find sample files (`sample-balance-csv.csv` and `sample-currency-csv.csv`) in the project directory.

## Contributing

This project is open source. Feel free to fork the repository and submit pull requests. You can find the source code at the GitHub link in the application header.
