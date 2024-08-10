# 📊 Financial Performance Dashboard Project

## 📝 Overview
This project involves the generation and analysis of financial data for 50 companies across various industries. The data is synthesized using Python libraries and is used to create an interactive Power BI dashboard. The dashboard provides insights into company performance, financial health, cash flow, investments, and risk assessment.

## 📈 Dashboard Sections

1. **Overview**
   - **Metrics**: Total Revenue, Total Assets, Net Income, Total Liabilities, EBITDA.
   - **Visuals**: KPI cards, trend lines for Revenue and Net Income.

2. **Financial Performance**
   - **Metrics**: Gross Profit, Operating Income, EBITDA, Net Income.
   - **Visuals**: Time-series charts and bar graphs for year-over-year comparisons.

3. **Balance Sheet Analysis**
   - **Metrics**: Total Assets, Total Liabilities, Equity.
   - **Visuals**: Stacked bar charts, line charts for equity trends, pie charts for composition.

4. **Cash Flow Analysis**
   - **Metrics**: Operating Cash Flow, Investing Cash Flow, Financing Cash Flow, Net Cash Flow.
   - **Visuals**: Waterfall charts, heatmaps, line charts for cash flow trends.

5. **Investments & Capital Expenditure**
   - **Metrics**: Capital Expenditure, Equity Investments, Investment Growth by Sector.
   - **Visuals**: Bar charts, scatter plots, trend lines for investment growth.

6. **Risk Assessment**
   - **Metrics**: Aggregate Risk Score, Debt Ratios, Industry-specific Risk Metrics.
   - **Visuals**: Gauges for risk, radar charts, heatmaps for high-risk areas.

## 🛠️ Files Generation and Verification

### Data Generation
- **Companies Data**: Generated using Faker to create realistic company profiles, including metrics like CompanyID, CompanyName, Industry, Sector, Region, YearFounded, NumberOfEmployees, CompanyType, RevenueCategory, StockTicker, MarketCap, HeadquartersCity, HeadquartersCountry, and LegalStructure.
  
- **Assets and Liabilities Data**: Synthesized to include metrics such as Cash, Accounts Receivable, Inventory, Property Plant Equipment, Short Term Debt, Long Term Debt, and corresponding totals for Assets and Liabilities.

- **Sales Data**: Includes generated values for Revenue and Cost of Goods Sold over a 5-year period.

- **Investments Data**: Contains Capital Expenditure and Equity Investment details over a 5-year period.

- **Financials Data**: Includes Revenue, Cost of Goods Sold, Gross Profit, Operating Income, Interest Expense, Tax Expense, Net Income, Depreciation, EBIT, EBITDA, and EBT.

- **Cash Flow Data**: Contains Operating, Investing, Financing Cash Flows, and Net Cash Flow.

### Data Verification
- **Consistency Checks**: Verified that total assets and liabilities match between financials and assets_liabilities tables.
- **Gross Profit Verification**: Checked that calculated gross profit aligns with reported values.
- **Net Income Verification**: Ensured that Net Income is consistent with the equation Operating Income - Interest Expense - Tax Expense.
- **Cash Flow Verification**: Verified that the Net Cash Flow equals the sum of Operating, Investing, and Financing Cash Flows.

## 🚀 Tools and Technologies Used
- **Python**: For data generation and verification using libraries like pandas, numpy, and Faker.
- **Power BI**: For creating an interactive dashboard that visualizes the generated data.

## 📂 Directory Structure
- **companies.csv**: Contains synthesized company data.
- **assets_liabilities.csv**: Contains data on company assets and liabilities.
- **sales.csv**: Contains sales data (Revenue, Cost of Goods Sold).
- **investments.csv**: Contains investment data (Capital Expenditure, Equity Investment).
- **financials.csv**: Contains detailed financial data (Revenue, Net Income, etc.).
- **cash_flow.csv**: Contains cash flow data (Operating, Investing, Financing, Net Cash Flow).

## 📝 Conclusion
This project leverages Python for data synthesis and Power BI for visualization, providing a comprehensive financial dashboard that can be used to assess company performance, financial stability, and risk.

## 📸 Screenshots
