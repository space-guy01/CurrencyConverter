# Currency Converter

This is a simple currency converter application that allows users to convert amounts between different currencies using the ExchangeRate-API.

## Features

- Select currencies from dropdown menus.
- Automatically update country flags based on selected currencies.
- Fetch real-time exchange rates and display converted amounts.
- Default currencies set to USD (from) and INR (to).

## Technologies Used

- HTML
- CSS
- JavaScript
- ExchangeRate-API

## How It Works

1. Users select the "From" and "To" currencies from the dropdown menus.
2. Users enter an amount to be converted.
3. Clicking the convert button fetches the latest exchange rate from the API.
4. The converted amount is displayed on the screen.
5. Country flags update dynamically based on the selected currencies.

## API Details

- Base URL: `https://v6.exchangerate-api.com/v6/166d0bec11590445a1efbecd/pair`
- API fetches real-time conversion rates between two selected currencies.

## Setup & Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/currency-converter.git
   ```
2. Navigate to the project directory:
   ```sh
   cd CurrencyConverter
   ```
3. Open `index.html` in a browser.

## Usage

- Select the desired currencies from the dropdown menus.
- Enter the amount to be converted.
- Click the "Convert" button to fetch the exchange rate and view the converted amount.

## License

This project is licensed under the MIT License.

## Author

- StackOrigin
- GitHub: [space-guy01](https://github.com/space-guy01)
- Email: arnavsince2009@gmial.com
