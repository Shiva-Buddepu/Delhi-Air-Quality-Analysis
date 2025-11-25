# Delhi Air Quality Analysis

This project analyzes the air quality of **Delhi** using the dataset **`delhiaqi.csv`**, which contains pollutant-level data such as CO, NO, NO₂, O₃, SO₂, PM2.5, PM10, NH₃ along with date information.  
The project performs time-series analysis, AQI calculation, pollutant trend visualization, correlation study, and patterns across hours and days.

---

##  Dataset Overview

**File:** `delhiaqi.csv`  
**Columns Included:**
- `date`
- `co`
- `no`
- `no2`
- `o3`
- `so2`
- `pm2_5`
- `pm10`
- `nh3`

The dataset contains daily pollutant concentration levels recorded in Delhi.

---

##  Project Workflow

### **1. Importing Necessary Libraries**
Used Python libraries such as:
- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly  
- sklearn (for AQI calculation logic if needed)

---

### **2. Importing and Cleaning the Data**
- Loaded the dataset  
- Handled missing values  
- Converted date column to datetime format  
- Sorted data chronologically  

---

### **3. Time Series Analysis of Pollutants**
- Visualized trends of major pollutants  
- Observed daily, monthly, and yearly variations  
- Identified seasonal pollution patterns  

---

### **4. Calculating Air Quality Index (AQI)**
- Computed AQI using standard Indian AQI formula  
- Derived individual sub-indices  
- Added final AQI column to dataset  

---

### **5. Analyzing AQI of Delhi**
- Observed AQI variation across the timeline  
- Highlighted high-pollution periods  
- Plotted AQI peaks and dips  

---

### **6. AQI Category Distribution**
Classified AQI into:
- Good  
- Satisfactory  
- Moderate  
- Poor  
- Very Poor  
- Severe  

Created charts showing AQI category counts and percentages.

---

### **7. Pollutant Concentration Analysis**
- Visualized average concentration of PM2.5, PM10, NO₂, O₃, SO₂, etc.  
- Identified pollutants contributing most to poor AQI  

---

### **8. Correlation Between Pollutants**
- Generated correlation heatmap  
- Identified strong relationships between pollutants (e.g., PM2.5 & PM10)  

---

### **9. Hourly Average AQI Trends (Jan 2023)**
- Extracted hourly data  
- Computed hourly mean AQI  
- Analysed daily pollution cycle  

---

### **10. Average AQI by Day of the Week**
Determined which weekday shows:
- Highest average AQI  
- Lowest average AQI  
- Patterns in weekday vs weekend pollution

---

##  Visualizations
The project contains rich and interactive visualizations, including:
- Line charts for pollutant trends  
- AQI distribution bar charts  
- Correlation heatmap  
- Hourly and weekday AQI visualizations  

---

