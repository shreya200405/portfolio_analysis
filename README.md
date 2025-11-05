# 📊 Portfolio Analysis using Python

## 📘 Project Overview
This project analyzes multiple stock prices, calculates returns, and helps understand portfolio performance over time.  
It compares individual stock behavior with the overall portfolio, measures risk, and identifies the best-performing assets.

---

## 🎯 Objectives
The goal of this project is to:

- Fetch stock price data using Python  
- Calculate daily and cumulative returns  
- Compare individual stock performance  
- Analyze correlation between stocks  
- Calculate portfolio returns and volatility  

---

## 🛠️ Tools & Libraries Used
- **Python**
- **NumPy** – for numerical calculations  
- **Pandas** – for data handling and analysis  
- **Matplotlib** – for visualizations  
- **yfinance** – for fetching real-time stock data  

---

## 💾 Dataset
The data is fetched using the **yfinance** library for Indian stocks such as:

- HDFC Bank (`HDFCBANK.NS`)  
- Infosys (`INFY.NS`)  
- Reliance (`RELIANCE.NS`)  
- TCS (`TCS.NS`)

---

## ⚙️ Process

1. Import stock data using **yfinance**  
2. Calculate **daily returns** and **cumulative returns**  
3. Create a **correlation matrix** to analyze stock relationships  
4. Build a **simple equal-weighted portfolio**  
5. Measure **portfolio volatility** and identify the **best-performing stock**

---

## 📈 Output Visualizations

### 📊 Stock Price Trends Over Time
Shows how each stock’s price has changed over the selected time period.  
![Stock price trends](images/stock_price_trends.png)

---

### 🔗 Correlation Between Stocks
Visualizes how closely the stock movements are related.  
A value closer to **1** means they move together; closer to **-1** means they move in opposite directions.  
![Correlation Matrix](images/correlation_matrix.png)

---

### 💹 Portfolio vs Individual Stocks (Cumulative Returns)
Compares portfolio growth with individual stock growth to measure overall performance.  
![Cumulative Returns](images/cumulative_returns.png)

---

## 🧾 Final Results

- Calculated **portfolio returns**, **volatility**, and **best-performing stock**  
- Found that **diversification reduces overall risk**  
- Identified **correlations between stocks**  

---

## 🧠 Key Learnings

- How to analyze financial data using Python  
- Importance of diversification in portfolio management  
- How correlation affects portfolio risk and return  

---

## 🚀 Future Enhancements

- Add more stocks for broader analysis  
- Include **risk-adjusted metrics** like the **Sharpe Ratio**  
- Create an **interactive dashboard** using **Streamlit** or **Power BI**

---

### 📂 Project Files
| File | Description |
|------|--------------|
| `portfolio.ipynb` | Jupyter notebook with complete analysis |
| `stock_price_trends.png` | Stock price trend visualization |
| `correlation_matrix.png` | Heatmap showing stock correlations |
| `cumulative_returns.png` | Portfolio vs individual stock performance |
| `README.md` | Project documentation |

---

### 👩‍💻 Author
**Shreya Goud**  
📍 Hyderabad, India  
💬 “Turning data into financial insights through Python and visualization.”

