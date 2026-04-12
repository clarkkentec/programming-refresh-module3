# Quantitative Finance Data Sources

## By Use Case

### Price Data
- **yfinance** (Phase 2) - Free, stocks/ETFs/indices, good for learning
- **Tiingo** (Module 7+) - Better quality, paid tiers, cleaner corporate actions
- **Alpaca** (Module 10) - Broker API, live trading focus

### Fundamental Data
- **Edgar Tools** (Module 7 Phase 3) - SEC filings, 13F holdings
- **Financial Modeling Prep** - Income statements, balance sheets
- **Quandl/Nasdaq Data Link** - Fundamental datasets

### Macro/Economic
- **FRED** (Phase 2 Session 10, Module 7 Phase 6) - Fed data, GDP, inflation
- **World Bank API** - International macro data
- **BLS** - Labor statistics

### Alternative Data
- **Quiver Quantitative** (Module 7+) - Congress trades, lobbying
- **Google Trends** - Search volume data
- **Social sentiment APIs** - Twitter/Reddit sentiment

### Derivatives
- **QuantLib** (Module 7 Phase 4) - Options pricing library (C++, Python bindings)
- **Options data APIs** - CBOE, broker APIs

## When to Use What

**Phase 2:** yfinance only (+ light FRED touch)
**Module 7 Phase 3 (Stat Arb):** Add Edgar Tools for fundamental factors
**Module 7 Phase 4 (Options):** Add QuantLib for pricing
**Module 7 Phase 6 (Macro):** Deep dive into FRED
**Module 10 (Live Trading):** Alpaca or similar broker API

## Notes
- Don't chase data sources until you need them for a specific strategy
- Better data ≠ better strategies (execution matters more)
- Start free (yfinance, FRED), upgrade when necessary


## Never needed unless going niche
**AKShare** (unless Asian markets)
**Quiver Quantitative** (unless alternative data focus)