# Global-co2-emission-project
#  Global CO₂ Emissions Tracker by Sector

### Objective  
This project analyzes and visualizes **global CO₂ emissions** across major sectors — **Energy, Transport, and Industry** — to identify top polluting countries, emission trends over time, and emission efficiency relative to population and GDP.  
The goal is to provide **data-driven insights** to support sustainable development and climate policy decisions.


## Project Overview
- **Dataset:** Multi-year CO₂ emissions data by country and sector  
- **Tools Used:** Python (Data Preparation), Tableau (Visualization), Excel (Validation)  
- **Outputs:**  
  - Cleaned and processed CSV files for visualization  
  - Interactive Tableau dashboard  
  - PDF Policy Brief summarizing top polluters  

## Project Workflow

### **1️ Data Collection**
- Source: `Co2_Emissions_by_Sectors.csv`  
- Contains emissions data for multiple countries, sectors, and years (2000–2022).

### **2️ Data Cleaning & Preparation (Python)**
Performed using `pandas`, `numpy`, and `matplotlib`.  
Key steps:
- Removed missing and inconsistent values.  
- Standardized column names and units.  
- Derived metrics:  
  - `CO₂ per capita` = Total CO₂ / Population  
  - `CO₂ per GDP` = Total CO₂ / GDP  
- Created:
  - `emissions_cleaned.csv` (summary-level data)  
  - `emissions_timeseries_long.csv` (long-format data for sector trends)

### **3️ Feature Engineering**
- Estimated missing energy emissions using energy consumption proxies.  
- Calculated sectoral emission shares:
  - Energy  
  - Transport  
  - Industry  
  - Agriculture  
  - Domestic  

### **4️ Visualization (Tableau)**
An interactive Tableau dashboard was built using the cleaned datasets.  
Key visuals:
-  **Global Map:** Total CO₂ emissions by country and year  
-  **Trend Line:** Emission trends across years  
-  **Stacked Bar Chart:** Sector-wise CO₂ distribution  
-  **Top 10 Per Capita Chart:** Countries with highest per-person emissions  
-  **CO₂ per GDP Chart:** Emission efficiency by economy  
-  **Filters/Slicers:** Year, Region, and Sector  


## Tools & Technologies
 **Python (pandas, numpy, matplotlib, reportlab)** | Data cleaning, transformation, and report generation 
 **Tableau** | Interactive dashboard creation and visual analytics 
 **Excel** | Data validation and exploration 
 **CSV / PDF** | Data storage and output formats 




