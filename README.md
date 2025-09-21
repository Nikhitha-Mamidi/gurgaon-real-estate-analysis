# Gurgaon Real Estate Dataset (2023)

This dataset contains raw, scraped real estate listing data from **Gurgaon**, India. It spans various types of properties including flats, independent houses, residential land, and society/apartment-level metadata.  
Collected in 2023 during the CampusX **Data Science Mentorship Program (DSMP 2023)**.
This repository contains a full analysis of Gurgaon real estate data using Python. The project has been extended to cover not only initial data exploration and feature engineering, but also advanced data preparation for Power BI business intelligence dashboards.

---

## 🏘️ Data Overview

| File Name                | Description |
|--------------------------|-------------|
| `flats.csv`              | ~3,000 listings of flats across Gurgaon, including price, sector, furnishing, etc. |
| `apartments.csv`         | Metadata about 248 apartment buildings: names, locations, and listed amenities |
| `independent_houses.csv` | 1,096 listings of bungalows and independent houses |
| `real_estate_societies.csv` | 248 rows detailing society-level information: available BHKs, nearby locations, and amenities |
| `residential_land.csv`   | 2,400 listings of available residential land across various sectors |

### Notebooks

- **Gurgaon_Real_Estate_Analysis.ipynb**  
  *Original project notebook:*  
  Includes initial data cleaning, feature derivation, and exploratory analysis on flat-type properties.

- **Gurgaon_Real_Estate_Analysis_2.ipynb**  
  *Extended, Power BI-ready notebook:*  
  Expands the analysis to cover multiple property types, advanced dataset integration and harmonization, comprehensive data cleaning, and calculation of business intelligence metrics. Also includes all steps followed to ensure full compatibility for Power BI import, and introduces analytical segments for stakeholder reporting and executive dashboarding.

### What's New in the Extended Analysis?

- Combines multiple CSV sources to create a more comprehensive market dataset
- Adds 50+ fields with advanced feature engineering and investment analytics
- Implements deeper data validation and outlier filtering
- Adds documentation for transparency and reproducibility, including handling of "Unknown" values  
- Prepares the final dataset for direct use in Power BI dashboards

---

**To use the Power BI-ready workflow, refer to `notebooks/Gurgaon_Real_Estate_Analysis_2.ipynb` for the latest steps, business logic, and export procedures.**


---

## 🔍 Raw Data Notice

⚠️ **This dataset is raw and may contain:**
- Missing values (`NaN`)
- Outliers
- Inconsistent formats
- Real-world noise/errors

It is ideal for demonstrating:
- Data cleaning pipelines
- Feature engineering
- Exploratory Data Analysis (EDA)
- Price prediction modeling

---

## 🎯 Purpose

Used for a capstone project on **real estate price prediction** and **property recommendation systems**, as part of the CampusX DSMP 2023.  
This data enables end-to-end application of data science techniques from cleaning to deployment.

---

## ⚠️ Disclaimer

- Data was scraped in **2023** from **99acres.com** for educational purposes only.
- No affiliation with 99acres or any real estate platform.
- Redistribution or commercial use is **not allowed**.
- This dataset is meant **strictly for academic and non-commercial** use.

---

## 📅 Data Collected: 2023  
📍 Location: Gurgaon, Haryana, India  
📁 Total Files: 5  


