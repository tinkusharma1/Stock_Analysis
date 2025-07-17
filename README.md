
# 📈 Stock Analysis Dashboard using Power BI

### 📊 Real-time and Historical Stock Market Visualization

This project focuses on building an interactive and automated stock analysis dashboard in **Power BI**, using financial data pulled from a public API. It helps in visualizing daily stock movements, volume, price fluctuations, and correlations.

---

## ✅ Key Features

- Real-time data connection using [Financial Modeling Prep API](https://site.financialmodelingprep.com/developer/docs)
- Visualize historical performance of selected stocks over 5 years
- Integrated cards for Opening, High, Low, and Closing prices
- Area and bar charts for transaction volumes
- Candlestick charts for daily stock movements
- Monthly and yearly filters for deep analysis
- Scatter plot to analyze correlation in price movements

---

## 📂 Dashboard Preview

![Dashboard](https://user-images.githubusercontent.com/78714438/168650248-f6288924-ea0b-4508-b20f-dc070af98d4f.png)

---

## 🚀 Project Steps

### 1. Get API Access
- Visit [Financial Modeling Prep](https://site.financialmodelingprep.com/developer/docs)
- Register for a free account (250 requests/day)
- Copy your unique API key from the dashboard

### 2. Fetching Company Quote
- Replace the default ticker (`AAPL`) with your preferred ticker (e.g., `AMZN`)
- Example URL:  
  `https://financialmodelingprep.com/api/v3/quote-short/AMZN?apikey=YOUR_API_KEY`

### 3. Load into Power BI
- Use `Get Data → Web` in Power BI
- Paste the API URL (replace `YOUR_API_KEY` with your actual key)
- Load and transform data using Power Query
- Click “Close & Apply” to view in Power BI

---

## 🔁 Historical Data for Time-Series Analysis

To visualize trends:
- Use daily historical data from the API  
  Example:  
  `https://financialmodelingprep.com/api/v3/historical-price-full/AMZN?apikey=YOUR_API_KEY`

- Load this data similarly via Web source
- Ensure table relationships are auto-detected based on the stock ticker

---

## 📊 Visualizations Used

- 📌 KPI Cards: Open, High, Low, Close, Symbol
- 📅 Slicers: Year & Month
- 📉 Line Chart: Historical Volume
- 💹 Candlestick Chart: Price Movement
- 🟢 Scatter Plot: Correlation in Price Fluctuations

---

## 📸 Snapshots

| Component | Preview |
|----------|---------|
| KPI Cards | ![KPI](https://user-images.githubusercontent.com/78714438/168648552-026b1e59-9e45-4cf8-b837-bde35280954b.png) |
| Filters | ![Filters](https://user-images.githubusercontent.com/78714438/168648742-c30449af-f35e-45c8-8e57-bcde73167503.png) |
| Scatter Plot | ![Scatter](https://user-images.githubusercontent.com/78714438/168649062-e948b0e2-9d29-44fe-aafc-f86fcc8afe80.png) |
| Volume Line Chart | ![Volume](https://user-images.githubusercontent.com/78714438/168649267-d35d0b97-bfd9-4573-b0c3-d81812c0f1f6.png) |
| Candlestick Chart | ![Candle](https://user-images.githubusercontent.com/78714438/168649491-b6097a20-b619-4d7f-9892-f3f1abd8336c.png) |

---

## 🛠 Tech Stack

- Power BI Desktop  
- Power Query  
- DAX Measures  
- Financial Modeling Prep API  
- JSON data transformation

---

## 📌 Notes

- The free API allows **250 requests/day**  
- Replace tickers in the URL for other stocks  
- Supports real-time & historical trend analysis
