# 🚗 Electric Vehicle Market Analysis (Web Scraping + EDA)

## 📄 Project Overview
This project focuses on **analyzing the Electric Vehicle (EV) market** using data collected through **web scraping**.  
It covers the complete data journey — from **scraping**, **cleaning**, and **preparation**, to **Exploratory Data Analysis (EDA)** and **business insights** visualization.

The goal is to uncover **key relationships** between EV features such as *price, battery capacity, range, efficiency,* and *acceleration*, and derive **actionable insights** for manufacturers, investors, and consumers.

---

## 🧩 Objectives
- Build a **web scraper** to extract real-world EV data.
- Clean and preprocess the dataset for accurate analysis.
- Perform **Univariate**, **Bivariate**, and **Multivariate** analysis.
- Derive **data-driven business insights** on price positioning, battery performance, and brand strategy.
- Visualize findings using clear and interactive graphs.

---

## 📊 Dataset Description
The dataset (scraped from EV databases) includes ~**973 EV models** across various brands and countries.

| Feature | Description |
|----------|-------------|
| `Brand` | Manufacturer name (e.g., Tesla, BMW, Volkswagen) |
| `Model` | EV Model name |
| `Price (€)` | Price in Euros |
| `Battery (kWh)` | Battery capacity |
| `Range (km)` | Real-world driving range |
| `Efficiency (Wh/km)` | Energy consumption per km |
| `Acceleration (0-100s)` | 0–100 km/h acceleration time |
| `Fastcharge (kW)` | Fast charging power |
| `Weight (kg)` | Vehicle weight |
| `Towing (kg)` | Towing capacity |
| `Cargo (L)` | Cargo volume |
| `Year` | Release year |
| `Segment` | Categorized as Budget / Mid-range / Premium |

---

## ⚙️ Tech Stack
- **Programming:** Python 🐍  
- **Libraries:**  
  `BeautifulSoup`, `Requests`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`  
- **Analysis Type:**  
  Univariate, Bivariate, Multivariate  
- **Tools:**  
  Jupyter Notebook, PowerPoint (for visualization summary)

---

## 🔍 Key Insights
1. **Battery–Range Correlation:** Strong positive correlation (~0.90) — higher battery capacity → longer range.  
2. **Performance Trade-off:** Negative correlation (~-0.74) between range and acceleration — faster cars often have lower range.  
3. **Price Drivers:** Price weakly correlates with specs, showing brand and luxury features often influence pricing.  
4. **Market Segmentation:**  
   - **Budget EVs:** Affordable, efficient, short-range urban models.  
   - **Mid-Range EVs:** Balanced design, moderate battery, and performance.  
   - **Premium EVs:** High battery capacity, performance, and luxury.  
5. **Top Brands:** Mercedes-Benz, Volkswagen, and Tesla lead EV innovation and diversity.

---

## 📈 Visualizations
The project includes:
- **Histograms & Boxplots** — Distribution of numeric features  
- **Heatmaps** — Correlation matrix of all numeric attributes  
- **Pairplots** — Feature interaction visualization  
- **Bar & Pie Charts** — Market share and brand comparisons  
- **Multivariate Charts** — Battery vs Range vs Price clusters  

*(All visuals available in the presentation `Ev_vehicle_webscrapping_proj_final.pptx` and Jupyter notebooks.)*

---

## 🧠 Business Impact
- Helps **manufacturers** identify key factors that influence range and pricing.  
- Aids **investors** and **analysts** in understanding competitive positioning.  
- Supports **consumers** in comparing EV performance and cost-value ratios.

---

