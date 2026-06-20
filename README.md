# 🇪🇺 European Energy Consumption Analysis  
### A Data Analytics Project Using Python, Pandas, Matplotlib & Seaborn

This project explores **energy consumption patterns across European countries**, with a special focus on **Ireland and Ukraine**.  
It includes data cleaning, exploratory analysis, visualizations, and an interactive dashboard preview.

---

## 📌 Project Overview

This analysis answers key questions:

- How does electricity consumption vary across Europe?
- How do Ireland and Ukraine compare in their **fuel mix** and **per‑capita energy use**?
- What trends can be observed in 2023–2024?
- Which countries consume the most energy per person?
- 
The visualisations reveal substantial variation in both total and per capita energy consumption across Europe. Large countries such as France, Germany, Italy, and the United Kingdom consistently exhibit the highest overall consumption, while smaller countries like Ireland display significantly lower levels. Fuel specific analyses highlight Ireland’s persistent reliance on oil and petroleum products.Overall, the study highlights the importance of transparent data preparation, interactive visualisation, and population adjusted metrics in understanding Europe’s evolving energy landscape.
The project uses:

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Custom visualizations**
- **GIF dashboard preview**

---

## 📂 Repository Structure

european_energy_consumption/
│
├── data/
│   ├── clean_energy.csv
│   ├── demo_pjan_linear.zip
│   ├── estat_ten00123.tsv
│
├── images/
│   ├── electricity_consumption_2024.png
│   ├── energy_analytics_dashboard.gif
│   ├── energy_consumption_heatmap.png
│   ├── energy_consumption_stacked_bar_ireland.png
│   ├── fuel_consumption_bar_chart_ie_ua.png
│   ├── fuel_consumption_ireland_ukraine_2023.png
│   └── per_capita_energy_2023.png
│
├── notebooks/
│   ├── energy_consumption_analysis.ipynb
│   ├── energy_analytics_dashboard.ipynb
│
└── README.md

## 📊 Key Visualizations

### 🔌 Electricity Consumption in 2024

![Electricity Consumption 2024](https://github.com/liudmyla-mysenko/european_energy_consumption/raw/main/images/elecricity_consumption_2024.png)

---

### 🗺️ Energy Consumption Heatmap

![Energy Consumption Heatmap](https://github.com/liudmyla-mysenko/european_energy_consumption/raw/main/images/energy_consumption_heatmap.png)

The chart highlights clear cross‑country differences in reliance on specific energy sources.  Darker cells indicate higher KTOE usage, with Germany, France, and the UK showing the highest values across fuels such as natural gas and oil products
---

### 🇮🇪🇺🇦 Ireland vs Ukraine Fuel Mix (2023)

![Fuel Mix](https://github.com/liudmyla-mysenko/european_energy_consumption/raw/main/images/fuel_consumption_ireland_ukraine_2023.png)

Ireland’s reliance on oil contrasts with Ukraine’s dependence on natural gas, while both countries show meaningful but different roles for electricity. These differences are important for understanding energy security, decarbonization strategies, and long‑term policy planning.
---

### 👥 Per‑Capita Energy Consumption (2023)

![Per Capita Energy](https://github.com/liudmyla-mysenko/european_energy_consumption/raw/main/images/per_capita_energy_2023.png)

By normalising total consumption against population size, this visualisation enables more meaningful cross-country comparisons and supports analysis of energy efficiency, sustainability, and socioeconomic factors.
---

## 📈 Interactive Dashboard Preview

![Dashboard Preview](https://github.com/liudmyla-mysenko/european_energy_consumption/raw/main/images/energy_analytics_dashboard.gif)

The dashboard presents both total energy consumption and per capita metrics, enabling users to explore data by year and country. Interactive elements such as dropdown filters and hover activated trend charts support dynamic exploration.
---

## 🧠 Skills Demonstrated

- Data cleaning & preprocessing  
- Exploratory data analysis (EDA)  
- Data visualization (Matplotlib, Seaborn)  
- Comparative analytics  
- Dashboard design  
- Clear documentation & storytelling  

---

## 🔧 How to Run the Project
1. Clone the Repository
bash
git clone https://github.com/liudmyla-mysenko/european_energy_consumption.git

cd european_energy_consumption

2. (Optional) Create a Virtual Environment
bash
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows

3. Install Dependencies

pip install -r requirements.txt
4. Run the Data Analysis Notebook (Optional)
This notebook performs data cleaning and exploratory analysis.

bash
jupyter notebook
Open:

Code
notebooks/energy_consumption_analysis.ipynb
Run all cells.

5. Run the Interactive Dashboard (Main Feature)
Open:

Code
notebooks/Energy Analytics Dashboard.ipynb
Run all cells.

✔ What happens next?
Dash starts running

You will see a message like:

Code
Dash is running on http://127.0.0.1:8050/
The dashboard will appear directly inside the Jupyter Notebook output  
(This is normal — Jupyter automatically embeds Dash apps.)

You can interact with:

A European energy consumption map

A trend chart that updates when you hover

Dropdown filters for year and metric
