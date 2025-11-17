# 🏡 London-Houses-Analysis 📊📍

## 📘 Overview
This project explores a **London Housing Dataset** to analyze property characteristics, price variations, and market patterns across London.  
The aim is to understand how different features — such as **location, size, property type, and amenities** — influence house prices.

The analysis was performed using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**, focusing on uncovering insights that explain pricing behavior and help identify key market drivers.

---

## 🧩 Dataset Information
**Source:** [Kaggle – Houses in London Dataset](https://www.kaggle.com/datasets/oktayrdeki/houses-in-london/data)  
**Rows:** *1000*
**Columns:** *17*  

### **Main Features:**
- 🏠 **Property Details:** `Type`, `Bedrooms`, `Bathrooms`, `Tenure`, `Size (Sq ft)`
- 📍 **Location Info:** `Latitude`, `Longitude`, `Postcode`, `Region`
- 💷 **Financial Data:** `Price`, `Ground Rent`, `Service Charge`
- 📅 **Listing Information:** `Date Listed`, `Seller`

---

## 🧹 Data Cleaning & Preparation
- Loaded the dataset using Pandas.
- Handled missing values in numerical and categorical columns.
- Converted price and size fields into numeric formats.
- Engineer new features:
  - `Price_per_sqft`
  - `Region` extraction
  - `Property Age` (if available)
- Removed duplicates.
- Normalized location coordinates for mapping.

---

## 📊 Visualizations & Insights

Below are examples of the key visualizations included in the analysis:

| Visualization | Description / Insight |
|--------------|------------------------|
| 🗺️ **Price Distribution by Region** | Shows that central London areas (Westminster, Kensington) have the highest average prices. |
| 🧱 **Price vs. Property Size (Sq ft)** | Larger houses are more expensive, but price increases are *non-linear*, especially in luxury zones. |
| 🛏️ **Bedrooms vs. Average Price** | Each additional bedroom significantly increases price, but with diminishing returns above 5 bedrooms. |
| 🏠 **Property Type Comparison** | Detached homes have the highest median prices; flats are most common and cheaper. |
| 🗂️ **Boxplot: Region vs. Price** | Reveals strong regional price variation and outliers in premium districts. |
| ⏳ **Time-Based Trend (If available)** | Prices show general upward movement with seasonal fluctuations. |

---

## 🪄 Tools & Libraries
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **NumPy**
- **Jupyter Notebook**

---

## 📈 Key Insights
- London’s **central districts** show extremely high property prices per square foot.
- **Size (sq ft)** is the strongest numerical predictor of price.
- **Property type** significantly influences value — with detached and semi-detached homes being premium.
- Prices are **not evenly distributed** across regions; location is the single biggest factor in cost.
- Some properties show **overpricing or underpricing**, making them potential investment opportunities.
- When analyzing **price vs bedrooms**, more bedrooms doesn’t always mean high price — location and size influence more.

---

## 🧠 Future Improvements
- Build a **machine learning model** to predict house prices.
- Create an **interactive geospatial dashboard** using Plotly or Folium.
- Add **postcode-level segmentation** to understand micro-market behavior.
- Perform **clustering** to identify hidden price groups.

---

## 🏁 Conclusion
This analysis provides a detailed view of London’s real estate market, highlighting how **location**, **property characteristics**, and **size** influence pricing.  
The insights can help buyers, sellers, and investors understand market patterns and make data-driven decisions.

---

## 🙌 Acknowledgments
This project is part of my data analysis learning journey.  
Special thanks to the Kaggle community for providing accessible datasets.

---

### 📂 Project Structure
├── London_houses_analysis.ipynb # Jupyter notebook with full analysis
├── houses_in_london.csv # Dataset
├── README.md # Project documentation

---

### 📬 Connect with Me
If you’d like to discuss this project or collaborate:

- 💼 LinkedIn: https://www.linkedin.com/in/mariam-yasser1-/
