# healthcare-trends-nl
Analysis of Dutch healthcare trends (2012–2025): diagnoses, specialisations, and costs

This project analyses **healthcare trends in the Netherlands**, focusing on:
- Most common diagnoses and how they change over time
- Specialisations with the highest workload
- Cost of treatment by specialisation and product

---

## 🗂 Data source

The data come from the **Open DIS dataset**, published by the  
[Nederlandse Zorgautoriteit (NZa)](https://www.nza.nl/) via the official Dutch open data portal:  
👉 [Overheid.nl – Open DIS data](https://data.overheid.nl/dataset/open-dis-data)

- License: **Public domain (Publiek domein)**
- Provider: **Nederlandse Zorgautoriteit (NZa)**
- Coverage: Aggregated hospital care data in the Netherlands, anonymised and publicly available.

### Files used in this project:
1. `DBC-Zorgproducten per jaar, specialisme, diagnose` – main dataset containing patient counts, diagnoses, specialisations, and average prices.  
2. `Referentietabel zorgproducten` – reference table for treatment products.  
3. `Referentietabel specialismen` – reference table for medical specialisations.  
4. `Referentietabel diagnoses` – reference table for diagnoses.  

---

## ⚙️ Tools
- R (readr, dplyr, ggplot2)
- Jupyter / Kaggle Notebooks
- GitHub for version control
