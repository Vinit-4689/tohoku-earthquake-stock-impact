# 📈 Shockwaves Through Markets: How the Tōhoku Earthquake Reshaped Risk and Return

---

## 📖 Project Overview
On March 11, 2011, the Tōhoku earthquake and tsunami struck Japan, causing massive devastation. This project explores the **impact of the Tōhoku earthquake on stock market returns and volatility** — specifically analyzing:

- **Nikkei 225** (Japanese stock index)
- **S&P 500** (U.S. stock index)

We used **daily returns data** to examine changes in:
- Mean Daily Returns
- Volatility (Standard Deviation of Returns)
- Behavior before and after the earthquake event.

---

## 🌀 Data Preparation

- Data Period: **February 1, 2011** to **May 1, 2011**
- Disaster Event: **Tōhoku Earthquake — March 11, 2011**
- Calculations:
  - Daily returns from price data.
  - Splitting the data into **Before** and **After** March 11, 2011.

---

## 🔢 Exploratory Data Analysis (EDA)

### 1. Mean Daily Returns (Before vs After)
- **Nikkei 225:**
  - Before Earthquake: Slightly positive returns.
  - After Earthquake: Significant negative drift.
- **S&P 500:**
  - Before Earthquake: Slightly negative.
  - After Earthquake: Shifted to positive average returns.

(Refer to "Impact on Mean Returns" Bar Plot)

---

### 2. Volatility Change (Standard Deviation of Returns)
- **Nikkei 225:**
  - Volatility nearly **tripled** post-earthquake.
- **S&P 500:**
  - Minor decrease in volatility.

(Refer to "Volatility Change" Bar Plot)

---

### 3. Timeline Behavior: Daily Returns Plot
- **Nikkei 225:**
  - Extreme downward spike immediately after March 11.
  - Followed by high volatility and fluctuations.
- **S&P 500:**
  - Much milder reaction.
  - Visible quick stabilization.

(Refer to "Daily Stock Market Returns" Line Plot)

---

## 🔄 Statistical Testing (T-Tests)
- **Nikkei 225:**
  - T-statistic: ~0.39
  - P-value: ~0.70
  - **Interpretation:** No statistically significant change in mean returns.

- **S&P 500:**
  - T-statistic: ~-0.87
  - P-value: ~0.39
  - **Interpretation:** No statistically significant change.

> Although the **visual impact and volatility** were severe for Nikkei, the average returns' statistical change was **not significant** at common levels (5%).

---

## 🔬 Key Insights
- Natural disasters can cause **sharp short-term disruptions** in local markets (Nikkei).
- **Global markets (S&P 500)** are often more resilient to region-specific disasters.
- **Volatility spikes** are more immediate and pronounced than long-term shifts in mean returns.
- **Emotional and panic selling** likely contributed to the post-earthquake turbulence.
- Investors should note: **Short-term volatility ≠ long-term trend reversal**.

---

## 🌐 Files Included
- `nikkei_sp500_returns.csv`
- `tohoku_earthquake_eda.ipynb`
- `volatility_change_plot.png`
- `mean_return_impact_plot.png`
- `daily_returns_timeline_plot.png`
- `INSIGHTS.md` (Detailed Insights)

---

## 🚀 Future Work
- Extending analysis to multiple global indices (FTSE, DAX, etc).
- Longer-term recovery patterns (6 months+).
- Sector-wise impact (Energy, Insurance, Infrastructure).

---

## 📅 Timeline Summary
- **Feb 1, 2011:** Data collection starts
- **Mar 11, 2011:** Tōhoku Earthquake hits
- **March 14, 2011:** Nikkei 225 plunges ~6% in a day
- **April 2011:** Signs of market stabilization appear

---

## 🔗 Connect
Feel free to fork this repo, suggest improvements, or connect with me!

---

> 💡 *"Markets are complex systems — disasters shake them, but resilience is built into their DNA."*

