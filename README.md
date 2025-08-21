# 📈 Stock Portfolio Tracker

A simple Python-based program to manage a stock portfolio by calculating total investment value using predefined (hardcoded) stock prices.

---

## 🚀 Features
- Accepts stock symbols and their quantities from the user.  
- Calculates the **total investment value** using predefined stock prices.  
- Displays a detailed **portfolio summary** (stock, quantity, price, value).  
- Option to **save the summary** in a text file (`portfolio_summary.txt`).  
- Input validation for incorrect stock symbols and quantities.  

---

## 🛠️ Technologies Used
- **Python 3**
- Core concepts: `dictionary`, `input/output`, `basic arithmetic`, `file handling`

---

## 📋 How It Works
1. User enters stock symbols and quantities.  
2. Program looks up stock prices from a **hardcoded dictionary**.  
3. It calculates the total investment = `price × quantity`.  
4. Displays a **portfolio summary**.  
5. (Optional) Saves results to a `.txt` file.  

---

## ▶️ Example Run
📈 Welcome to Stock Portfolio Tracker
Available Stocks: AAPL, TSLA, GOOGL, MSFT, AMZN
Enter stock symbol (or type 'done' to finish): AAPL
Enter quantity for AAPL: 5
Enter stock symbol (or type 'done' to finish): TSLA
Enter quantity for TSLA: 3
Enter stock symbol (or type 'done' to finish): done

--- Portfolio Summary ---
AAPL: 5 shares × $180 = $900
TSLA: 3 shares × $250 = $750

Total Investment Value: $1650
Do you want to save the result to a file? (yes/no): yes
✅ Portfolio saved to portfolio_summary.txt

yaml
Copy
Edit

---

## 📂 File Output (portfolio_summary.txt)
--- Portfolio Summary ---
AAPL: 5 shares × $180 = $900
TSLA: 3 shares × $250 = $750

Total Investment Value: $1650

yaml
Copy
Edit

---

## 🔮 Future Enhancements
- Add support for **CSV/JSON export**.  
- Allow **custom stock price input**.  
- Display **percentage contribution** of each stock.  
- Integrate with an **API for live stock prices**.  

---
