# Geopolitical Oil Market Analysis (2015–2025)

> ⚠️ **Note:** This repository is for demonstration purposes only.  
> Full code, datasets, and models are private but available on request.

📖 **Published Research:**  
[Impact of Geopolitical Tensions on Oil Market Volatility and Currency Movements](https://jccair.org/index.php/jcai/article/view/3)

This repository contains code, datasets, and visualizations from my published research:
**"Impact of Geopolitical Tensions on Oil Market Volatility and Currency Movements"**
published in the *Journal of Computing and Artificial Intelligence*.

---

## 📊 Project Overview
This project integrates:
- **GARCH-based oil price volatility modeling**
- **Event study methodology** for pre- and post-event market analysis
- **Sentiment analysis** (manual + TextBlob) on geopolitical news
- **XGBoost-based machine learning models** to predict currency moves
- **Interactive Power BI dashboards** with KPI cards, slicers, and event markers

---

## 🗂 Repository Structure
- `data/` – Cleaned datasets (or samples)
- `notebooks/` – Jupyter notebooks for analysis
- `dashboards/` – Power BI `.pbix` file
- `report/` – Published paper & documentation
- `figures/` – Exported charts and visualizations (see below)

---

## ⚙️ Installation
```bash
pip install -r requirements.txt
```

📊 Key Visualizations
1️⃣ Interactive Dashboard Overview
![Dashboard](https://github.com/hamza9407/geopolitical-oil-market-analysis/blob/cb9a997c35a1ff7721dc96ae0a9254926ac2b5fa/dashboard.png)
2️⃣ Oil Prices (2015–2025)
![Oil Prices](https://github.com/hamza9407/geopolitical-oil-market-analysis/blob/760306b5c21017be0f7164161b9efd12f074fcb9/oil_prices.png)
3️⃣ Oil Price Volatility (GARCH Modeled)
![Oil GARCH Volatility](https://github.com/hamza9407/geopolitical-oil-market-analysis/blob/760306b5c21017be0f7164161b9efd12f074fcb9/oil_prices_garch_volatility.png)
4️⃣ Oil Prices vs Defence Spending
![Oil vs Defence](https://github.com/hamza9407/geopolitical-oil-market-analysis/blob/760306b5c21017be0f7164161b9efd12f074fcb9/oil_price_vs_defence.png)
5️⃣ Oil Prices vs Defence (with key political events)
![Oil vs Defence 2](https://github.com/hamza9407/geopolitical-oil-market-analysis/blob/760306b5c21017be0f7164161b9efd12f074fcb9/oil_prices_vs_defence.png)
6️⃣ PKR Movement During Events
![PKR Movement](https://github.com/hamza9407/geopolitical-oil-market-analysis/blob/760306b5c21017be0f7164161b9efd12f074fcb9/pkr_movement.png)

📑 Results

!Key findings:

Negative geopolitical sentiment correlates with higher oil volatility

PKR depreciates significantly during major geopolitical escalations

Power BI dashboard allows event-wise dynamic filtering & drillthrough analysis
