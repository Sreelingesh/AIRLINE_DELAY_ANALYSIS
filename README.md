# Airline Delay Data Exploration Project

### Introduction
Flight delays are a major concern in aviation, creating difficulties for both passengers and airlines.  
This project investigates flight data with the aim of finding insights and patterns behind delays.  
The workflow uses Python for analysis and visualization, along with tools like SQL, Excel, and Power BI.

---

### Project Deliverables
- Datasets prepared and cleaned for reuse  
- Visualizations from exploratory data analysis (EDA)  
- An interactive dashboard to support business insights  

---

### Tools & Technologies
- Excel → For early-stage cleaning  
- SQL → For data queries and transformation  
- Python → For analysis and visualization (Pandas, Matplotlib, Seaborn)  
- Power BI → For dashboard design and reporting  

---

### Data Files
- flight_details.csv → Raw flight dataset containing airline names, departures, arrivals, delays, and cancellations  
- flight_details_cleaned.csv → Cleaned dataset with missing values handled, duplicates removed, names standardized, and derived fields like Delay_Category  
- final_flight_data.csv → Final dataset after EDA, ready for dashboard and reporting  

---

### Exploratory Data Analysis
Performed in Jupyter Notebook (flight_analysis_fixed.ipynb) with plots saved in the folder:  
EDA_Analysis_ipynb/EDA_screenshots/  

Focus areas included:  
1. Average departure delay by airline  
2. Delay vs on-time flight proportions  
3. Seasonal/monthly delay trends  
4. Route-specific delay behavior  

---

### Dashboard
The dashboard (Airline_Analysis_Dashboard) provides:  
- Summarized view of delays  
- Easy interpretation of bottlenecks for airlines  
- Helpful tool for service quality improvement  


```
## Project Structure  

Airline_Delay_Analysis
1) Datasets
* flight_details.csv                -Raw dataset
* flight_details_cleaned.csv        - Cleaned dataset used in analysis
* final_flight_data.csv             - Final dataset for dashboard

2) EDA_Analysis_ipynb/
* flight_analysis_fixed.ipynb       - Jupyter Notebook (EDA + cleaning)
* EDA_screenshots                   - Saved plots from EDA

3) Dashboards
* Airline_Analysis_Dashboard        - Final dashboard
*  README.md                        - Project documentation

### Steps to Reproduce
1. Download or clone this repository  
2. Install required Python packages  
3. Open flight_analysis_fixed.ipynb in Jupyter Notebook  
4. Run all cells to regenerate analysis and plots  



### Key Insights
- Certain airlines have consistently higher delay times  
- Seasonal spikes in delays exist during specific months  
- Majority flights are on-time, but even small percentages of delays affect travelers  
- Dashboard offers a practical way to monitor delay statistics  



### Conclusion
This project illustrates the complete data pipeline:  
- Cleaning and preparing flight datasets  
- Conducting exploratory analysis  
- Producing visualizations and dashboards  

The results are beneficial to passengers, regulators, and airlines, helping them minimize delays and improve travel efficiency.  
