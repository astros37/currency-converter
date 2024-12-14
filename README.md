# Currency Converter

A simple Python script that fetches the latest exchange rates and converts currencies based on user input.

## Features
- Fetches live exchange rates from a free API.
- Converts any amount from one currency to another.
- Simple command-line interface (CLI) for easy interaction.

## Requirements
- Python 3.x
- Internet connection (to fetch live exchange rates).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/currency-converter.git
   cd currency-converter
   ```

2. Install the required libraries:
   ```bash
   pip install requests
   ```

## Usage
1. Run the script:
   ```bash
   python currency_converter.py
   ```

2. Follow the prompts to:
   - Enter the amount you want to convert.
   - Specify the source currency (e.g., USD).
   - Specify the target currency (e.g., EUR).

3. View the converted amount in the console.

## Example
### Input:
```text
Enter amount: 100
From currency (e.g., USD): USD
To currency (e.g., EUR): EUR
```

### Output:
```text
100 USD = 92.34 EUR
```

(Note: The exchange rate is fetched live and may vary.)

## API Used
The script uses the [ExchangeRate-API](https://www.exchangerate-api.com/) to fetch real-time exchange rates. You can replace the API URL in the script with your own API key or another exchange rate provider.

## Contributing
Feel free to fork this repository and submit pull requests to improve the script. All contributions are welcome!

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

