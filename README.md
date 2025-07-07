
# 📈 IPO Analysis and Beta Value Calculation for Global Health Limited (Medanta)

This repository contains an in-depth analysis of the **Initial Public Offering (IPO)** of [Global Health Limited (Medanta)](https://www.medanta.org/), along with the calculation of its **Beta value** using Python and financial market data.

---

## 🏥 Project Overview

### Company: Global Health Limited (Medanta)
- **Incorporated:** May 23, 2008
- **IPO Date:** November 7, 2022 (Closing)
- **IPO Size:** ₹2205.57 Cr
- **Listing Price:** ₹401  
- **Current Price (As of Feb 14, 2025):** ₹1114.5  
- **Ticker Symbol:** `MEDANTA.NS` (NSE)

### Project Goals
- Analyze the IPO fundamentals, financial health, and business outlook of Medanta.
- Understand SEBI regulations governing IPOs.
- Estimate the **Beta coefficient** of Medanta stock using market data (NIFTY 50 as the benchmark).
- Explore investment risks and opportunities using both fundamental and quantitative tools.

---

## 📊 Contents

### 1. 📑 IPO Analysis
- Company history and expansion strategy.
- Detailed IPO structure (Fresh Issue + Offer for Sale).
- Promoter holdings and share lock-in periods.
- Regulatory framework under SEBI ICDR Regulations (2018).
- Competitive positioning and healthcare industry overview.

### 2. 📈 Beta Calculation
We use **historical weekly return data** of Medanta and NIFTY 50 to compute Beta, which measures stock volatility relative to the market.

#### 📌 Tools & Libraries
- `yfinance`: For fetching historical stock data.
- `pandas`, `numpy`: For data manipulation and statistics.
- `matplotlib`: For plotting return correlation.

#### 💻 Code Snippet
```python
import yfinance as yf
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Download weekly adjusted close prices
# ... (See full code in `beta_calculation.ipynb`)
````

#### 🔍 Result

```
Calculated Beta for MEDANTA.NS against ^NSEI: 0.56
```

> A beta of 0.56 indicates that Medanta is **less volatile** than the overall market.

---

## 📂 Files in This Repo

| File/Folder               | Description                                                                    |
| ------------------------- | ------------------------------------------------------------------------------ |
| `ipo_analysis.md`         | Detailed qualitative IPO analysis, regulatory overview, and industry insights. |
| `beta_calculation.py`     | Python script to fetch data and calculate the Beta value.                      |
| `stock_beta_analysis.csv` | Weekly return data used for beta calculation.                                  |
| `README.md`               | Project overview and usage guide.                                              |

---

## 📈 Sample Plot

![Beta Scatter Plot](https://github.com/chandan22140/IPO-Analysis-of-Global-Health-Limited-Medanta/blob/21d7ce06c72738777aa2b8ef03882776865bfef3/plot.png)
*Scatter plot of Market Returns vs Stock Returns — Linear trend implies Beta*

---

## 👥 Contributors

* Chandan Sah (2022140)
* Abhay Kohli (2022015)
* Prajil Bhagat (2022359)

---

## 📜 License

This project is for academic and educational use only. No commercial use permitted without permission.

---

## 🚀 How to Run the Beta Script

1. Install dependencies:

   ```bash
   pip install yfinance pandas numpy matplotlib
   ```

2. View the plot and check `stock_beta_analysis.csv` for export data.

---

## 🔍 References

* [SEBI ICDR Regulations, 2018](https://www.sebi.gov.in)
* [Medanta DRHP](https://investmentbank.kotak.com/downloads/global-health-limited-DRHP.pdf)
* CRISIL Report on Indian Healthcare
* [NSE India](https://www.nseindia.com/)



