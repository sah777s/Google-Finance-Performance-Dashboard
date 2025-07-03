# Google-Finance-Performance-Dashboard
## 🎯 Project Objective:

To design a comprehensive Power BI dashboard that integrates income statement, balance sheet, cash flow, and stock price data of Alphabet Inc. (GOOGLE), enabling stakeholders to analyze financial performance, cash flow health, profitability trends, and stock behavior over time for informed decision-making.

 <a href=https://github.com/sah777s/Google-Finance-Performance-Dashboard>Dashboard</a>

 ##  💼 Business Questions

- What is the trend of total revenue over the last 12 quarters?

- Is net income increasing or declining over time?

- How does operating cash flow compare to net income?

- Can operating cash flow cover the company’s investing and financing needs?

- What is the current debt-to-equity ratio and what does it imply about financial leverage?

- How do major expenses (R&D, SG&A, cost of revenue) affect profitability?

- How is the gross profit margin trending quarter-over-quarter?

- What is the trend in GOOGLE’s stock price, and how does it correlate with financial performance?

## 🔁 Project Process

1. **Data Collection**  
   - Imported financial datasets: `income_statement`, `balance_sheet`, `cash_flow_statement`, and `daily_stock_prices`.

2. **Data Cleaning**  
   - Removed blanks and errors, converted units, validated values (e.g., common stock, cash flow), and ensured consistency in fiscal dates.

3. **Data Modeling**  
   - Connected all financial tables via `fiscalDateEnding`.  
   - Created a custom **Date Table** for DAX time intelligence functions.

4. **DAX Measures**  
   - Developed dynamic measures for:
     - `Total Revenue`, `Net Income`, `EBITDA`, `Operating Cash Flow`
     - `Gross Profit Margin`, `Debt-to-Equity Ratio`, `Cash Flow Coverage`
     - `Cash-to-Income Ratio`, `Stock Price Change %`, `Latest Close`

5. **Data Visualization**  
   - Line charts, stacked bars, and KPI cards show trends and ratios over time.  
   - Filters and slicers control interaction across visuals (e.g., disabling cross-filtering where needed).

6. **Insight Generation**  
   - Answered core business questions related to financial performance, cash flow quality, cost drivers, and stock behavior.

---

- Is deferred revenue growing, indicating strong future customer commitments?

- Is the company consistently buying back shares or issuing dividends?

- ## 📷 Dashboard Preview

- ![image url](https://github.com/sah777s/Google-Finance-Performance-Dashboard/blob/3d18602d0fec85983eb403f660179ec64ec10c41/Screenshot%202025-07-01%20203951.png)
- ![image url](https://github.com/sah777s/Google-Finance-Performance-Dashboard/blob/3d18602d0fec85983eb403f660179ec64ec10c41/Screenshot%202025-07-01%20204847.png)
- ![image url](https://github.com/sah777s/Google-Finance-Performance-Dashboard/blob/3d18602d0fec85983eb403f660179ec64ec10c41/Screenshot%202025-07-01%20205333.png)
- ![image url](https://github.com/sah777s/Google-Finance-Performance-Dashboard/blob/3d18602d0fec85983eb403f660179ec64ec10c41/Screenshot%202025-07-01%20205344.png)

##  📊 Project Insights

- Total revenue showed consistent quarterly growth, indicating strong market demand and stable business operations.

- Net income tracked closely with revenue but had sharper fluctuations due to operational and non-operational expenses.

- Operating cash flow consistently exceeded net income, highlighting high-quality earnings and strong internal liquidity.

- Cost of revenue remained the largest expense, followed by R&D and SG&A, directly influencing gross profit margin trends.

- Gross profit margin stayed stable, suggesting effective cost control despite revenue fluctuations.

- The debt-to-equity ratio remained low (~0.06), reflecting minimal reliance on debt financing.

- Cash flow from financing was significantly negative, primarily due to share buybacks, not liquidity stress.

- Deferred revenue was negligible or missing, suggesting most revenue is recognized immediately rather than deferred.

- Stock prices generally aligned with earnings, but occasional divergence pointed to market anticipation or investor sentiment.

- Financial KPIs like cash-to-income ratio and coverage ratio were above 1, signaling financial robustness and operational efficiency.

## ✅ Final Conclusion

The dashboard provides a clear, data-driven view of GOOGLE’s financial health, revealing consistent revenue growth, strong operational cash flow, controlled debt, and a shareholder-friendly financing strategy. It serves as a reliable decision-support tool for investors, analysts, and stakeholders.



