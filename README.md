# Weather Monitoring Dashboard (Power BI)

An interactive Power BI dashboard that integrates live weather data and air quality metrics to provide a real-time view of environmental conditions.

The dashboard is designed for monitoring key weather indicators and air quality levels, enabling quick interpretation of current conditions.

---

## Dashboard Preview

<img width="1484" height="832" alt="Screenshot 2026-02-18 at 1 35 42 AM" src="https://github.com/user-attachments/assets/1b9f2a35-4d76-4624-a16c-b857ee3fc49c" />


---

## Objective

Provide a centralized view to:

- Monitor current weather conditions  
- Track key environmental metrics such as temperature, humidity, wind speed, and pressure  
- Observe short-term forecast trends  
- Understand air quality levels across multiple pollutants  

---

## Dashboard Overview

The dashboard supports quick situational awareness by presenting real-time environmental data in a structured and easily interpretable format.

---

## Key Features

### Current Weather Overview
- Temperature and weather condition  
- Visibility, humidity, pressure, wind speed, precipitation, and UV index  

### Forecast Analysis
- 7-day temperature trend  
- Chance of rain visualization  

### Sunrise and Sunset
- Daily sunrise and sunset timings  

### Air Quality Monitoring
Pollutants tracked:
- O3 (Ozone)  
- PM2.5  
- SO2  
- NO2  
- CO  
- PM10  

### AQI Status
Air quality categorized into:
- Good  
- Moderate  
- Unhealthy for Sensitive Groups  
- Unhealthy  
- Very Unhealthy  
- Hazardous  

### AQI Suggestions
Health recommendations based on AQI levels  

### Conditional Formatting
Color-coded indicators to highlight air quality severity  

---

## Key Metrics

- Temperature (°C)  
- Wind Speed (mph)  
- Pressure (inHg)  
- Humidity (%)  
- Visibility (miles)  
- UV Index  
- Precipitation (inches)  
- Air Quality Index (AQI)  

---

## Tech Stack

- Power BI  
- Power Query (M)  
- DAX  
- Weather API  

---

## Project Scope

This project focuses on building a real-time monitoring layer for environmental data. The emphasis is on data integration, transformation, and interactive visualization rather than long-term data warehousing or predictive analytics.

---

## System Design Considerations

The dashboard is built using an API-driven data extraction approach optimized for simplicity and rapid deployment.

For production-scale implementations, the solution can be extended to support:

- Persistent storage using databases such as PostgreSQL or Snowflake  
- Scheduled data ingestion pipelines for continuous updates  
- Near real-time reporting capabilities  
- Historical data modeling for long-term trend analysis  
- Alerting mechanisms for high-risk environmental conditions  

This approach allows the dashboard to evolve into a scalable environmental monitoring system.

---

## Summary

This project demonstrates:

- Integration of external APIs into Power BI  
- Data transformation using Power Query  
- Use of DAX for calculated metrics and conditional logic  
- Development of an interactive dashboard for environmental monitoring  
