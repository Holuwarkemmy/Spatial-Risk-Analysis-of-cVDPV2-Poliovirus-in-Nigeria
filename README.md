# Spatial Risk Analysis of Circulating Vaccine-Derived Poliovirus Type 2 (cVDPV2) in Nigeria


## 1. Introduction

Nigeria has made significant progress towards polio eradication; however, the continued circulation of **circulating vaccine-derived poliovirus type 2 (cVDPV2) remains a major public health concern. Persistent outbreaks are often driven by immunity gaps, high population concentration, and uneven surveillance performance, necessitating targeted and data-driven responses.
Traditional tabular surveillance reports offer limited insight into where transmission risk is concentrated and how interventions should be prioritised geographically. Spatial analysis provides a powerful means of transforming surveillance data into actionable intelligence for immunisation planning and outbreak prevention.
This project applies GIS-based spatial analysis and interactive data visualisation to assess cVDPV2 risk at Local Government Area (LGA) level in Nigeria, producing a composite risk index and an operational decision-support dashboard.



## 2. Aim and Objectives

### Aim

To identify, classify, and visualise LGA level cVDPV2 transmission risk in Nigeria in order to support targeted public health interventions.

### Objectives

• Aggregate ward-level cVDPV2 case data to the Local Government Area (LGA) level and integrate population density to assess transmission potential.
• Develop a composite spatial risk index to classify LGAs by cVDPV2 transmission risk.
• Visualise and communicate high-risk LGAs through an interactive dashboard to support targeted immunisation and surveillance planning.


## 3. Data Sources

### Datasets Used

• Ward level cVDPV2 Surveillance Data
• GRID3 Nigeria LGA boundary shapefile
• Population Density Raster for under 5 years 



## 4. Methodology

### 4.1 Spatial Data Processing (QGIS)

1. **Data Harmonisation**
   • Standardised coordinate reference systems (CRS)
   • Cleaned and harmonised LGA and ward names

2. **Ward-to-LGA Aggregation**
   • Ward-level case data spatially joined to LGA boundaries
   • Case counts aggregated using sum to derive total cases per LGA

3. **Population Density Integration**
   • Zonal statistics applied to extract mean population density for each LGA

4. **Risk Scoring**
   • Case counts classified into five ordinal risk scores (1–5) using natural breaks
   • Higher scores represent greater epidemiological concern

5. **Composite Risk Index Development**
   • Combined:
     • Total cVDPV2 cases  
     • Case-based risk score  
     • Mean population density  
   • LGAs classified into:
     • Very Low Risk  
     • Low Risk  
     • Moderate Risk  
     • High Risk  
      Very High Risk  



### 4.2 Dashboard Development (Power BI)

The final processed dataset was imported into Power BI to develop an interactive dashboard featuring:
• National choropleth map of cVDPV2 risk by LGA  
• Distribution of LGAs by risk category  
• Top 10 high-risk LGAs by composite risk index  
• Summary indicators for total cases and priority LGAs  
• Interactive filters by state and risk class



## 5. Results

### 5.1 National cVDPV2 Burden

- **Total reported cVDPV2 cases:** **7,759**
- **LGAs classified as High or Very High Risk:** **27**

Although the majority of LGAs fall into lower risk categories, a small subset accounts for a disproportionate share of national transmission risk.



### 5.2 Spatial Distribution of Risk

The national risk map reveals that cVDPV2 risk in Nigeria is highly clustered, rather than evenly distributed.

• Most LGAs fall within Very Low or Low Risk categories  
• High and Very High Risk LGAs form distinct spatial clusters, particularly in:
  • Northern urban centres  
  • Densely populated peri-urban areas  

This pattern suggests sustained local transmission rather than isolated outbreaks.



### 5.3 Risk Category Distribution

• Very Low Risk - 462
• Low Risk - 223
• Moderate Risk - 57
• High Risk - 17
• Very High Risk - 10

**Key Insight:**  
Only 3.5% of LGAs fall into High or Very High Risk categories, highlighting the efficiency gains of risk-based geographic prioritisation.



### 5.4 Top High-Risk LGAs

The highest-priority LGAs identified include:

• Sokoto North (Sokoto) – 1,048 cases (Risk Index: 4.60)  
• Maiduguri (Borno) – 1,015 cases (4.20)  
• Katsina (Katsina) – 787 cases (4.20) 


**Key Insight:**  
Urban LGAs with high population density dominate the high-risk ranking, reinforcing their role as transmission amplifiers.



## 6. Discussion

The analysis demonstrates that cVDPV2 transmission risk in Nigeria is spatially concentrated and predictable. High-risk LGAs are characterised by:
• High case burden  
• High population density  
• Urban or peri-urban settings  

LGAs with elevated risk indices but comparatively lower reported cases may indicate surveillance gaps or emerging transmission, underscoring the value of the composite risk index beyond raw case counts.



## 7. Public Health Implications and Recommendations

### 7.1 Immunisation Planning
• Prioritise Supplementary Immunisation Activities (SIAs) in High and Very High Risk LGAs  
• Strengthen routine immunisation in Moderate Risk LGAs to prevent escalation  

### 7.2 Surveillance Strengthening
• Expand environmental surveillance in high-risk urban LGAs  
• Improve AFP case detection sensitivity in identified clusters  

### 7.3 Resource Allocation
• Allocate vaccines, logistics, and personnel based on risk ranking
• Focus interventions where the public health return is highest

### 7.4 Monitoring and Early Warning
• Use the dashboard as a dynamic monitoring tool
• Track changes in LGA risk classification over time



## 8. Limitations

• Absence of WASH and immunisation coverage data limited causal interpretation  
• Surveillance data subject to under-reporting  
• Population density used as a proxy rather than a direct measure of transmission  



## 9. Conclusion

This project demonstrates how GIS-driven spatial analysis combined with interactive dashboards can enhance polio eradication efforts. By identifying geographic concentrations of cVDPV2 risk, the approach supports efficient, targeted, and evidence-based public health decision-making.

The methodology is scalable and transferable to other infectious diseases requiring spatial risk prioritisation.



## 10. Tools and Skills

• QGIS (spatial aggregation, zonal statistics, risk modelling)  
• Power BI (interactive dashboards, mapping, ranking)  
• Spatial epidemiology  
• Public health analytics  
• GIS for decision support 
