# healthcare-trends-nl
Analysis of Dutch healthcare trends (2012–2025): diagnoses, specialisations, and costs

This project analyses **healthcare trends in the Netherlands**, focusing on:
- Most common diagnoses and how they change over time
- Specialisations with the highest workload
- Cost of treatment by specialisation and product

📊 **Full analysis available on Kaggle:**  
➡ [Click to view the project on Kaggle](https://www.kaggle.com/code/marialukash/healthcare-trends-in-the-netherlands-2012-2025/)

---
## Define the problem

**Business context:**  
This analysis explores trends in Dutch healthcare based on open data from the NZa (Nederlandse Zorgautoriteit).  
Healthcare costs and patient volumes are key topics in the Netherlands due to an aging population and rising care demand.

**Goal:**  
To identify trends in patients, costs, and medical specialisations between 2012–2025.

**Key questions:**
1. Which diagnoses are the most common, and how do they change over time?  
2. Which specialisations handle the largest number of patients?  
3. Where are treatments the most expensive?
---
## 🗂 Data source

The data come from the **Open DIS dataset**, published by the  
[Nederlandse Zorgautoriteit (NZa)](https://www.nza.nl/) via the official Dutch open data portal:  
👉 [Overheid.nl – Open DIS data](https://data.overheid.nl/dataset/open-dis-data)

**Key features of the dataset:**
- 📌 *License:* Public domain (Publiek domein)  
- 🏥 *Provider:* Nederlandse Zorgautoriteit (NZa)  
- 🇳🇱 *Coverage:* Aggregated hospital care data in the Netherlands  
- 🔒 *Privacy:* Fully anonymised and publicly available  

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

## 📈 Key Insights
### **📈 1. Top 10 most common diagnoses per year (2012–2025)**
![diagnoses_trend](images/diagnoses_trend.png)

## ✅ Conclusions & Recommendations

### **Conclusions**
The analysis of Dutch healthcare data from 2012–2024 reveals a clear long-term increase in both patient volume and treatment costs, particularly within cardiovascular care and oncological specialties. These trends are primarily driven by demographic aging, improved access to healthcare, and enhanced diagnostic capabilities. Surgical and internal medicine specializations consistently manage the highest number of patients, while cardiothoracic surgery, cardiology, and rehabilitation account for the majority of healthcare expenditures.

### **Recommendations**
- **💓 Increase investment in cardiovascular prevention and management**  
  Early intervention can reduce long-term treatment costs and improve patient outcomes.
- **🏥 Expand capacity in high-demand medical specialisations**  
  Particularly in surgery and internal medicine, where patient volume remains consistently high.
- **🧑‍⚕️ Prioritise rehabilitation infrastructure**  
  Rising survival rates after major procedures lead to long-term demand for rehabilitation care.
- **🧬 Improve early detection and awareness programs for oncology**  
  Continuous growth in skin cancer cases highlights the need for screening and prevention strategies.
