# 📊 Crypto Portfolio Tracker

**Crypto Portfolio Tracker** is a Python application that helps track cryptocurrency investments. It uses the Binance API to fetch current crypto prices and updates an Excel file with new values and percentage gains/losses.

## 🚀 Features

✅ **Cryptocurrency tracking**: Automatically fetches prices via the Binance API.  
✅ **Portfolio updates**: Calculates new token amounts and their value in USDT.  
✅ **Gains and losses calculation**: Evaluates investment performance in percentage terms.  
✅ **Excel file creation and update**: Manages crypto data in a structured format.  
✅ **Intuitive CLI interface**: Allows easy creation and management of the Excel file.

## 📂 Project Structure

```
CryptoPortfolio/
│── file_update.py        # Handles file updates and modifications
│── menu.py               # CLI menu for user interactions
│── my_cryptos.xlsx       # Excel file containing crypto data
│── requirements.txt      # List of Python dependencies
```

## 🛠️ Installation

### 1️⃣ Clone the project
```bash
git clone https://github.com/your-repo/CryptoPortfolio.git
cd CryptoPortfolio
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the main script
```bash
python menu.py
```

## 📊 Excel File Format

The **my_cryptos.xlsx** file contains the following information:

| Symbol | Token Amount | New Token Amount | New Value | Gains/Losses (%) |
|--------|-------------|-----------------|-----------|------------------|
| BTC    | 0.05       | 0.0489          | 1500.00   | -3.20%          |
| ETH    | 1.20       | 1.15            | 2400.00   | +5.50%          |

## 🎯 Usage

1️⃣ **Create a new Excel file**
```bash
python menu.py
```
2️⃣ **Update an existing Excel file**
```bash
python file_update.py
```
3️⃣ **Track your crypto performance**
```bash
python menu.py
```

## 🔐 Technologies Used

- **Python** 🐍: Main programming language.
- **OpenPyXL** 📄: Excel file manipulation.
- **Requests** 🌍: Fetching crypto prices via Binance API.
- **Psutil** ⚙️: Detects open Excel processes to prevent writing errors.

## 📜 License

This project is licensed under **MIT**. See the [LICENSE](LICENSE) file for more information.

---

💡 *Want to contribute? Feel free to open an issue or a pull request!* 🚀
