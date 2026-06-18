# CodeAlpha_Investment_Portfolio_Analysis
# 📈 Multi-Asset Dynamic Portfolio Construction Model

A professional, dynamic asset allocation and trade execution model built in Google Sheets to simulate an institutional-grade wealth management dashboard. This portfolio is strategically designed for a **Moderate Risk** profile with a total capital allocation of **₹1,00,000**.

## 🚀 Live Project Links
*   **Interactive Google Sheet:** [https://docs.google.com/spreadsheets/d/1PzTlxwbSa_KWB7d9oYclmpWXQ6XnaYkqMierTGJv6Hs/edit?usp=sharing]
*   **Strategic Report (PDF):** 

---

## 📊 Key Features Implemented

*   **Live Market Data Integration:** Uses `=GOOGLEFINANCE()` to fetch real-time pricing for Indian equities (`NSE`) and global digital currencies (`CURRENCY:BTCINR`).
*   **Fractional Share Execution Simulation:** Automatically handles real-world exchange constraints by rounding down buy orders (`=INT()`) to ensure no partial shares are bought on Indian exchanges.
*   **Automated Liquidity Accounting:** Dynamically tracks exact uninvested cash reserves sitting in the brokerage ledger due to share rounding errors.
*   **Data Aggregation Summary:** Implements `=SUMIF()` arrays to feed an independent asset class matrix and render a real-time allocation breakdown visual.

---

## 📂 Repository Structure

```text
├── README.md               # Project overview and documentation
└── Portfolio_Report.pdf    # Full 1-2 page strategic rationale and asset breakdown 
