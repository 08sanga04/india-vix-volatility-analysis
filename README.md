# india-vix-volatility-analysis
Analysis of India VIX vs market range and volatility using Excel pivot tables
# India VIX & Market Volatility Analysis

## 📌 Project Overview
This project analyzes the relationship between **India VIX (Volatility Index)** and **index price behavior** to understand how volatility impacts **intraday price range** and **directional movement**.

The goal of this analysis is to determine:
- Whether higher volatility leads to wider intraday ranges
- Whether volatility provides any directional edge
- How market behavior changes across different volatility regimes

---

## 📂 Dataset Description
The dataset consists of **daily index-level OHLC data** combined with **daily average India VIX values**.

### Key Columns:
- **Date**
- **Open, High, Low, Close**
- **Daily Average India VIX**

---

## 🧮 Feature Engineering
To better quantify market behavior, the following derived metrics were created:

- **High–Low (H–L):** Measures intraday price range (volatility proxy)
- **High–Open (H–O):** Upper price expansion
- **Open–Low (O–L):** Lower price expansion
- **Open–Close (O–C):** Directional movement

These metrics help separate **volatility effects** from **directional bias**.

---

## 📊 Monthly Pivot Table Analysis
Monthly pivot tables were created to compute average values for:
- **India VIX**
- **Intraday Range (H–L)**
- **Directional Movement (O–C)**
- **Closing Price**

This allowed comparison of market behavior across months and volatility regimes.

---

## 🔍 Key Insights
- **Higher VIX months (April–May)** consistently show **wider intraday ranges**, confirming a strong volatility–range relationship  
- **Low VIX months (July–September)** exhibit **range compression**, indicating reduced trading opportunity  
- **Directional movement (O–C)** remains inconsistent across months, demonstrating that **volatility does not imply direction**  
- The findings suggest that volatility is better suited for **range-based and options strategies** rather than directional prediction  

---

## 📈 Practical Applications
- Volatility regime identification
- Options and volatility strategy selection
- Range trading and breakout filtering
- Market behavior analysis for risk management

---

## 🛠 Tools & Techniques Used
- Microsoft Excel
- Pivot Tables
- Feature Engineering
- Time-based aggregation
- Financial market analysis

---

## 🚀 Conclusion
This project demonstrates that **India VIX is a strong indicator of intraday range expansion**, but not of market direction.  
Effective trading and risk strategies should therefore adapt to **volatility conditions** rather than rely on directional assumptions.

---

## 📎 Notes
This project complements SQL-based trading performance analysis by focusing on **market volatility behavior** using spreadsheet-based analytics.
