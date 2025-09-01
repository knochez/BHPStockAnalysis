# BHP Stock Analysis (2005–2025)

End-to-end financial analysis of **BHP Group Limited (ASX: BHP)** covering 20 years of monthly stock price history.  
The project combines **Python (EDA + visualization)** and **SQL (query-based insights)** to demonstrate practical data analysis, risk assessment, and reporting.

---

## Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, CleaningBox  
- **SQL**: SQLite (queried inside Jupyter, while combining with Python to execute each query)  
- **Jupyter Notebook** for workflow + reporting  

---

## Analysis Highlights

### 1. Descriptive Statistics
- Min, max, mean, median, standard deviation of closing price.  
- Long-term **CAGR**: steady 5.96% annualized growth.  
- Best monthly return: +33.6% (Aug 2008).  
- Worst monthly return: –18.5% (Mar 2016).  

### 2. Volatility & Price
- **12-month rolling volatility** to capture calm vs. stormy periods.  
- Major spikes align with **2008 GFC**, **2015 commodity crash**, and **2020 COVID**.  
- Dual-axis plots overlay price vs. volatility.  

### 3. Drawdowns
- Worst drawdown: –63.6% from Mar 2011 peak ($37.56) to Jan 2016 trough ($13.67).  
- Recovered by Dec 2020.  

### 4. Moving Averages
- 12M vs. 36M moving averages plotted with **Golden Cross** / **Death Cross** markers.  
- Highlights long-term commodity cycles and trend reversals.  

### 5. SQL Queries
Executed 5 SQL queries on the dataset to complement Python analysis:
1. Highest & lowest close price.  
2. Average yearly return.  
3. Year with worst monthly return.  
4. Average trading volume by decade.  
5. Top 5 best monthly returns with dates.  

---

## Deliverables
- **Jupyter Notebook**: full EDA + SQL queries  
- **Charts**: price vs volatility, drawdown shading, moving averages  
- **SQLite database**: loaded directly from Pandas DataFrame  

---

## Key Takeaways
- BHP shows **long-term growth** but is highly cyclical, with severe drawdowns during global crises.  
- Combining **Python + SQL** demonstrates versatility across data wrangling, statistical analysis, and database querying.  
- This project balances **quantitative rigor** with **visual storytelling**.  
