# 📊 Data Analysis with Pandas & Matplotlib

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat-square&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-11557c?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![Internship](https://img.shields.io/badge/Internship-Project%201-orange?style=flat-square)

---

## 🔍 Overview

A data analysis project built using **Python**, **Pandas**, and **Matplotlib** that loads a CSV dataset, performs statistical analysis, and generates interactive visualizations to extract meaningful business insights.

This was developed as **Slab 1 (Beginner Level)** during my data science internship.

---

## ✨ Features

- 📥 **CSV Loading** — Reads structured data using `pandas.read_csv()`
- 📐 **Statistical Analysis** — Computes mean, median, standard deviation, min/max across selected columns
- 📊 **Bar Charts** — Monthly comparison of key business metrics
- 📈 **Line Charts** — Trend analysis over time
- 🔵 **Scatter Plots** — Correlation and distribution analysis
- 🌡️ **Heatmaps** — Normalised multi-metric performance overview
- 💡 **Auto Insights** — Trend percentage, peak detection, seasonal patterns

---

## 📁 Project Structure

```
data-analysis/
├── data/
│   └── business_data.csv       # Input dataset
├── notebooks/
│   └── analysis.ipynb          # Jupyter notebook walkthrough
├── src/
│   ├── load_data.py            # CSV loading & preprocessing
│   ├── statistics.py           # Statistical computations
│   └── visualizations.py       # Chart generation functions
├── output/
│   └── charts/                 # Saved plot images
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10 | Core language |
| Pandas | Data loading, cleaning, and analysis |
| Matplotlib | Bar, line, scatter plot generation |
| Seaborn | Heatmap and styled visualizations |
| NumPy | Numerical computations (std dev, averages) |
| Jupyter Notebook | Interactive development and presentation |

---

## 📊 Sample Visualizations

### Bar Chart — Monthly Sales
Displays month-wise sales performance, allowing quick identification of high and low revenue periods.

### Scatter Plot — Sales vs Customers
Reveals the positive correlation between customer count and total sales revenue.

### Heatmap — All Metrics (Normalised)
Stacked view of Sales, Profit, Units Sold, and Customers normalised to 0–100% for side-by-side seasonal comparison.

---

## 📌 Key Insights Discovered

- 📈 Sales grew **+71.4%** from January to December
- 🏆 Peak performance consistently in **Q4 (Oct–Dec)**
- 📉 A mid-year dip in **February** across all metrics — typical seasonal pattern
- 📊 Q4 average is **~38% above** the annual mean, indicating strong year-end momentum
- 🔗 Strong positive correlation (r ≈ 0.98) between Customers and Sales

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/data-analysis-pandas.git
cd data-analysis-pandas

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the analysis script
python src/visualizations.py

# 4. Or open the Jupyter notebook
jupyter notebook notebooks/analysis.ipynb
```

**requirements.txt**
```
pandas>=2.0
matplotlib>=3.7
seaborn>=0.12
numpy>=1.24
jupyter
```

---

## 📈 Statistics Computed

| Metric | Formula | Output |
|--------|---------|--------|
| Average | `df[col].mean()` | Central tendency |
| Std Dev | `df[col].std()` | Spread of data |
| Maximum | `df[col].max()` | Peak value |
| Minimum | `df[col].min()` | Lowest value |
| Total | `df[col].sum()` | Cumulative sum |
| Trend % | `(last - first) / first * 100` | Growth rate |

---

## 🎯 Learning Outcomes

- Loading and preprocessing CSV data with Pandas
- Performing descriptive statistics on real-world datasets
- Creating publication-quality charts with Matplotlib
- Interpreting data trends and communicating insights clearly
- Structuring a data science project for reproducibility

---

## 🙋 Author

**Your Name**
📧 your.email@example.com
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | [GitHub](https://github.com/your-username)

> *Built during Data Science Internship — 2024*

---

⭐ **If you found this helpful, please star the repo!**
