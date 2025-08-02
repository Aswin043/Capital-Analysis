# 🌍 Disaster Data Analysis for Optimal Insurance Coverage 🏥📊

This project analyzes natural disaster datasets to identify regions with low-risk profiles ideal for expanding affordable insurance coverage. It combines geospatial analysis, correlation insights, and hypothesis testing to support data-driven decisions for insurance strategy.

---

## 📌 Project Overview

Insurance companies often face challenges in identifying profitable regions for coverage expansion, especially when balancing affordability with risk. This project provides actionable insights by:

- Analyzing correlations between natural disasters and insured damages
- Identifying countries with low casualties and damage
- Recommending optimal expansion zones for affordable insurance plans

---

## 🧾 Methodology

1. **Data Collection**  
   - Global disaster records sourced from EM-DAT and other public datasets
   - Variables include event type, affected population, casualties, and damages

2. **Data Cleaning & Wrangling**  
   - Removed incomplete or inconsistent records
   - Standardized country names, time frames, and damage units

3. **Exploratory Data Analysis (EDA)**  
   - Trends in disaster frequency by region
   - Correlation between damages and population affected
   - Identification of outlier events

4. **Statistical Analysis**  
   - Correlation matrix to find significant relationships
   - Hypothesis testing to validate assumptions about low-risk zones

5. **Geospatial Visualization**  
   - Interactive maps highlighting high vs low risk zones
   - Target region flags for expansion consideration

---

## 📍 Key Insights

- Countries like **Thailand, Malaysia, Pakistan, Serbia, and Greece** show low levels of both casualties and insured damages.
- These regions present a **low-capital requirement** opportunity for launching or expanding insurance products.
- A strong correlation was found between total affected and total damages, validating the use of casualty data as a proxy for financial risk.

---

## 🛠️ Tools & Technologies

- **R Language** (Data wrangling, hypothesis testing, visualization)
- **Quarto / QMD Reports** (Professional client-facing reporting)
- **ggplot2, dplyr, leaflet, sf** (Visualization and geospatial tools)

---

## 📊 Visualizations

- Heatmaps showing disaster impact by country
- Choropleth maps for insured damages and affected population
- Scatter plots revealing disaster-damage correlations

---

## 🔍 Future Improvements

- Integrate real-time disaster monitoring APIs (e.g. GDACS)
- Incorporate socioeconomic factors like GDP, HDI, and insurance penetration
- Build a dashboard for dynamic region selection and premium simulations

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- EM-DAT International Disaster Database
- RStudio and Quarto documentation
- Academic literature on insurance risk modeling and geospatial analysis

---

