# CaseStudy_AQI
# **Air Quality and Public Health Analysis** 🌍💡

## **Project Overview** 🚀
This project analyzes the impact of air quality on public health using real-time air quality data. The primary focus is on evaluating how air pollution affects respiratory and cardiovascular health, identifying regional disparities, studying temporal trends, and building predictive models. Additionally, urbanization and industrialization effects are explored based on the dataset.

---

## **Objectives** 🎯
1. **Assess the Impact of Air Quality on Respiratory Diseases**  
2. **Evaluate the Effect of Air Pollution on Cardiovascular Health**  
3. **Identify Regional Disparities in Health Outcomes Related to Air Quality**  
4. **Examine Temporal Trends in Air Quality and Public Health**  
5. **Develop Predictive Models for Health Outcomes Based on Air Quality Forecasts**  
6. **Evaluate the Effect of Urbanization and Industrialization on Public Health in Relation to Air Quality**  

---

## **Dataset** 📊
The dataset used for this project is titled **"Real_time_Air_Quality_Index_from_various_locations.csv"**. It contains real-time air quality data, including pollutant measurements and the geographical location of the observations. Key columns in the dataset include:

- `pollutant_id`: Type of pollutant (e.g., PM2.5, PM10)  
- `pollutant_min`, `pollutant_max`, `pollutant_avg`: Minimum, maximum, and average pollutant values for each record  
- `city`: The city where the data was collected  
- `last_update`: Timestamp of the data collection  

---

## **Steps and Methodology** 🛠️

### **1. Data Preprocessing and AQI Calculation**  
- Data was loaded, cleaned, and processed.  
- AQI was computed from available pollutant data using EPA breakpoints for PM2.5 and PM10.

### **2. Exploratory Data Analysis (EDA)**  
- **Regional Analysis**: AQI distribution was visualized across cities/regions using boxplots.  
- **Temporal Analysis**: AQI trends were analyzed over time using time series plots.

### **3. Simulation of Health Outcomes**  
- Respiratory and cardiovascular cases were simulated based on AQI values.  
- Correlations between AQI and health outcomes were analyzed.

### **4. Predictive Modeling**  
- A linear regression model was built to predict respiratory cases from AQI.  
- The model's performance was evaluated using Mean Squared Error (MSE) and R-squared.

### **5. Urbanization and Industrialization Analysis**  
- A proxy for urbanization was created based on city frequency, with cities appearing more frequently classified as "Urban" and others as "Rural".  
- Health outcomes were compared between urban and rural areas.

---

## **Key Findings** 📌
- **Air Quality and Health**: Poor air quality (higher AQI) is associated with higher cases of respiratory and cardiovascular diseases.  
- **Regional Disparities**: Urban areas tend to have worse air quality than rural areas, leading to more severe health outcomes.  
- **Predictive Models**: The linear regression model showed a strong correlation between AQI and respiratory health, with potential for real-world health outcome forecasting.

---

## **How to Run the Project** 🏃‍♂️🏃‍♀️

### **1. Clone the Repository**  
Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/air-quality-public-health.git
