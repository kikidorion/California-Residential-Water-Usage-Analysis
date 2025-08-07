# California-Residential-Water-Usage-Analysis
This project analyzes California's Urban Retail Water Supplier data to build a predictive model for Residential Gallons Per Capita Daily (R-GPCD) usage.   The notebook uses a **Random Forest Regressor to identify the most influential factors driving water consumption, incorporating seasonality, climate zones, regions, and multiple demand categories

# California Water Usage Analysis – A Predictive Model

## 📌 Overview
This project builds a **predictive Random Forest model** to forecast Residential Gallons Per Capita Daily (**R-GPCD**) for California urban retail water suppliers.  
By identifying the **top predictors** of water usage, it informs **data-driven water conservation policy**.

The work integrates:
- **Data cleaning & preprocessing** in Python
- **Machine learning** (Random Forest Regressor)
- **Exploratory data analysis & feature importance visualization**
- **Policy recommendations** visualized in **Tableau**

---

## 📊 Key Findings
- **Top Predictors**: `POTABLE_VOL_SOLD_GAL` & `POTABLE_SUPPLY_GAL` had the strongest influence, followed by `NET_USAGE_GAL`.
- **Seasonality**: The `MONTH` variable was a significant factor, with peaks in summer months.
- **Geospatial Effects**: `CLIMATE_ZONE` & `HYDRO_REGION` had moderate but consistent influence.

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `California Water Usage Analysis - A Predictive Model.ipynb` | Full Jupyter Notebook with Python code & visualizations |
| `suppliers.csv` | Raw dataset (from California Open Data Portal) |
| `final_randomforest_model_output.csv` | Model predictions, residuals, and features |
| `policy_brief.pdf` | Policy brief summarizing methodology & recommendations |
| `README.md` | This documentation file |

---

## 🔗 Live Links
- **🔍 Tableau Dashboard Story** → [View on Tableau Public](YOUR_TABLEAU_LINK_HERE)
- **📄 HTML Notebook** → [View Interactive Notebook](YOUR_HTML_NOTEBOOK_LINK_HERE)
- **📊 CSV Model Output** → [Download CSV](YOUR_CSV_FILE_LINK_HERE)
- **📑 Policy Brief PDF** → [Download PDF](YOUR_PDF_LINK_HERE)

---

## 📚 Data Source
California Open Data Portal – **Urban Retail Water Supplier (URWS) Conservation Supply & Demand Dataset**  
[https://data.ca.gov/dataset/urban-water-supplier-water-production-and-conservation-reporting](https://data.ca.gov/dataset/urban-water-supplier-water-production-and-conservation-reporting)

---

## ⚙️ Requirements
Install dependencies before running the notebook:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
