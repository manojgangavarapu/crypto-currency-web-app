# Crypto Currency Web App

![Crypto Currency Web App](logo.png)

## 📊 Project Description
This web app retrieves real-time cryptocurrency prices and market insights from **CoinMarketCap**. Built using **Streamlit**, it offers visualizations like bar charts, pie charts, and historical price trends to help users analyze crypto performance.

## 🚀 Features
- **Real-Time Price Tracking**: Live data from CoinMarketCap.
- **Market Metrics**: Bitcoin & Ethereum dominance, total market cap.
- **Customizable Charts**: Bar plots, pie charts, and historical line graphs.
- **Download Data**: Export crypto price data as CSV.

## 📁 Files
- **`installations.sh`**: Automates environment setup with required Python libraries.
- **`crypto_price_app.py`**: Main application code for the crypto dashboard.

## ⚙️ Installation
1. **Clone the Repository:**
   ```bash
   https://github.com/manojgangavarapu/crypto-currency-web-app
   ```

2. **Run Installation Script:**
   ```bash
   https://shell.cloud.google.com/?show=ide%2Cterminal&authuser=1&fromcloudshell=true
   ```
   This will:
   - Upgrade `pip`
   - Install `pipenv`
   - Set up a virtual environment
   - Install required libraries (`streamlit`, `pandas`, `matplotlib`, `seaborn`, `bs4`, `cryptocmd`)

## 🖥️ Usage
1. **Activate Virtual Environment:**
   ```bash
   pipenv shell
   ```

2. **Run the Web App:**
   ```bash
   streamlit run crypto_price_app.py
   ```

3. **Access the App:**
   https://8080-cs-86913e24-6d82-4eb3-aa57-a4261bc234c8.cs-asia-southeast1-ajrg.cloudshell.dev/?authuser=1

## 📊 Visualizations
- **Bar Plot:** % price change over 1h, 24h, or 7d.
- **Market Cap Analysis:** Bar charts for selected cryptocurrencies.
- **Market Share:** Pie chart for BTC, ETH, and altcoins.
- **Historical Trends:** Line graphs for price trends over the last 30 days.

## 📦 Dependencies
- Python 3
- Streamlit
- Pandas
- Matplotlib
- Seaborn
- BeautifulSoup4
- CryptoCMD

## 🤝 Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature-xyz`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-xyz`).
5. Open a pull request.


