# Housing-Affordability-Victoria
Analyzing housing affordability trends in Victoria (2010–2024) using price-to-income ratio

# 🏠 Housing Affordability in Victoria (2023)

This project explores housing affordability across 31 Local Government Areas (LGAs) in Greater Melbourne. Using housing market data and 2021 Census income data, I evaluated where homes are affordable, where they're not — and how this relates to household income, distance to CBD, and demographic patterns.

---

## 📌 Objective

To assess housing affordability in Victoria by analyzing:
- Median house and unit prices (2023)
- Median weekly household income (2021)
- Price-to-income ratios
- Mortgage stress levels
- Household demographics (size, vehicles, children)

---

## 📂 Data Sources

- **Property prices (by suburb):** Domain/REIV, 2013–2023
- **Census data (by LGA):** ABS 2021 — income, vehicles, families
- **Suburb–LGA mapping:** Manually created & verified
- **Distance to CBD:** Google Maps (Flinders Street Station)

---

## 🧮 Methodology

- Mapped 600+ suburbs to 31 LGAs
- Calculated median house and unit prices per LGA
- Merged income and demographic stats from ABS
- Computed:
  - House & unit price-to-income ratios
  - Estimated mortgage repayment vs income
  - Regional persona snapshots

---

## 📊 Key Metrics

| LGA        | House Price | Income (Weekly) | Ratio | Monthly Mortgage | Stress % |
|------------|-------------|------------------|--------|------------------|----------|
| Melton     | $642,500    | $1,887           | 6.5    | $1,800           | 22%      |
| Glen Eira  | $1,760,750  | $2,133           | 15.9   | $4,500           | 50%+     |
| Wyndham    | $653,500    | $2,033           | 6.2    | $1,930           | 22%      |
| Boroondara | $2,629,000  | $2,376           | 21.3   | $6,000+          | Extreme  |

---

## 🔍 Insights

- 🔴 Inner LGAs like **Stonnington** and **Boroondara** are deeply unaffordable (price-to-income ratio > 20).
- 🟢 Outer LGAs like **Melton**, **Wyndham**, and **Hume** offer better affordability but are more car-reliant.
- 🚗 LGAs with low public transport and long CBD distance tend to have **higher car ownership and household size**.
- 🧒 Family-friendly LGAs like **Cardinia** and **Casey** have more children per family and lower unit affordability.

---

## 🧑‍🤝‍🧑 Regional Persona Examples

### **Boroondara – The Affluent Inner Elite**
> High income, low household size, extreme house price. Central professionals with low affordability despite wealth.

### **Casey – The Young Family Belt**
> Large families, multiple vehicles, growing population. Affordability better, but stress building in outer SE.

### **Melbourne – Singles and Students**
> Small households, renters dominate. Expensive housing, but fewer cars, smaller spaces.

---

## 📈 Visualizations

- 📍 **Scatter Plot**: Distance to CBD vs Price-to-Income Ratio
- 📉 **Bar Chart**: Top 10 Least Affordable LGAs
- 🔵 **Bubble Chart**: Income vs House Price
- 🗺️ (Planned) Heat Map: Mortgage Stress Zones

See visuals in `/charts/`

---

## 🗂️ File Structure


---

## ✅ Conclusion

This project illustrates the gap between income and property prices across Melbourne. While inner suburbs are expensive due to demand and location, outer suburbs show signs of mortgage stress and car dependency. Data reveals how affordability is not just a price issue — it's a demographic and infrastructure story.

---

## 💼 About Me

I'm an aspiring data analyst based in Melbourne, passionate about applying data to real-world problems. This project was built using Excel, Google Sheets, Python (Colab), and GitHub to demonstrate my skills in:

- Data wrangling and cleaning
- Geospatial and demographic analysis
- Insight communication
- Visual storytelling

