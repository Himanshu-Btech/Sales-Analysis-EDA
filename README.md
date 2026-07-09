# Sales EDA — Superstore Dataset

Exploratory data analysis of ~10,000 retail orders to uncover what's driving 
profitability, using pandas, numpy, matplotlib, and seaborn.

## 📊 Key Findings

- **Sales grew ~4x from 2014 to 2017**, with strong seasonal spikes every 
  Nov–Dec (holiday shopping) followed by a sharp January drop.
- **Discounts above ~20% turn orders unprofitable on average** — the 41–60% 
  discount range is the most damaging, averaging a $134 loss per order.
- **Furniture is the weakest category overall**, and is the only 
  Category-Region combination running an outright loss (Central region, -$2,871).
- **A single product line — Cubify CubeX 3D Printers — accounts for nearly 
  $12,700 in total losses**, while one product (Canon imageCLASS 2200 
  Advanced Copier) alone generated $25,199 in profit.

## 🔍 What's inside

| Analysis | Technique |
|---|---|
| Data cleaning & feature engineering | pandas (datetime conversion, derived columns) |
| Outlier detection on order size | numpy (Z-scores) |
| Monthly sales trend | matplotlib line plot |
| Category × Region profitability | seaborn heatmap |
| Discount vs Profit relationship | seaborn scatter plot |
| Profit by discount tier | seaborn bar plot |
| Top/bottom performing products | matplotlib subplots |

## 🛠️ Tools
Python · pandas · numpy · matplotlib · seaborn · Google Colab

## 📁 Files
- `Sales_Analysis.ipynb` — full analysis notebook
- Dataset: [Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?resource=download)

## 📌 Note
Dataset was pre-cleaned — no missing values were found across any of the 
9,994 records (verified via `.isnull().sum()`).
