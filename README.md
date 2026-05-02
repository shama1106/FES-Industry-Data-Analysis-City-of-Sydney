# 📊 FES Industry Data Analysis – City of Sydney

<p align="center">
  📈 Data Analytics | 🌍 Spatial Analysis | 📊 Power BI Dashboard | 🌐 Web Application
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue">
  <img src="https://img.shields.io/badge/Visualization-Power%20BI-yellow">
  <img src="https://img.shields.io/badge/Web-React%20|%20TypeScript-green">
  <img src="https://img.shields.io/badge/Database-Supabase-orange">
  <img src="https://img.shields.io/badge/Auth-Clerk-red">
</p>

---

## 📊 Project Overview

This project analyses **industry patterns and employment trends in Sydney** using the **City of Sydney Open Data Hub (FES dataset)**.

It provides:
- Industry growth & decline analysis  
- Geographic distribution of businesses  
- Economic insights across regions  
- Interactive dashboards + web platform  

---

## 🎯 Business Problem

Sydney faces:
- 📉 Decline in traditional industries (Retail, Manufacturing)  
- 📈 Growth in service sectors (Hospitality, Legal, Tech)  
- ⚖️ Unequal distribution of industries across regions  
- 🎓 Skill gaps vs industry demand  

👉 This project helps stakeholders make **data-driven decisions**

---

## 🧠 Project Architecture

```
Raw Data → Python Cleaning → Processed Dataset → Power BI Dashboard → Web Application
```

---

## 🔧 DATA CLEANING (PYTHON)

### 📂 Dataset
- Source: City of Sydney Open Data Hub  
- Rows: 64,622  
- Features: 18 columns  

### 🔹 Key Cleaning Steps

- Removed missing values (X, Y coordinates)  
- Removed duplicate records  
- Standardized text fields (lowercase, trimmed)  
- Created new column: **Location Summary**  
- Converted coordinates:
  - UTM → Latitude & Longitude (using `pyproj`)  

---

## 📊 DATA ANALYSIS & INSIGHTS

### 📈 Industry Trends

#### 🔹 Growth Sectors
- Professional Services  
- Hospitality (Restaurants, Cafes)  
- Financial Services  

#### 🔻 Declining Sectors
- Retail Trade  
- Manufacturing  

---

### 📍 Geographic Insights

- **CBD & Harbour**
  - Legal + Financial services dominate  

- **Other Regions**
  - Restaurants dominate  
  - Social & cultural hubs  

---

### 📊 Key Findings

- Restaurants & cafes show consistent growth  
- Legal services highly centralized in CBD  
- Retail decline due to online shopping  
- Co-working spaces emerged in 2017  

---

## 📊 DASHBOARD (POWER BI)

> Note: The interactive Power BI dashboard requires university account access.  
> Dashboard screenshots are provided below for public portfolio viewing.

### 🔹 Main Dashboard
![Dashboard Overview](images/dashboard-main.png)

### 🔹 Growth Analysis
![Growth Dashboard](images/dashboard-growth.png)

### 🔹 Industry Distribution Map
![Map Dashboard](images/dashboard-map.png)

---

### ✨ Features

- Dynamic filters (Year, Village, Industry)  
- Drill-down capabilities  
- Interactive map (Latitude/Longitude)  
- Real-time insights  

---

## 🌐 WEB APPLICATION

### 🔹 Tech Stack

- React + TypeScript + Vite  
- TailwindCSS + ShadCN UI  
- Supabase (Database)  
- Clerk (Authentication)  

---

### 🔹 Features

- 🔐 User login system  
- 📊 Dashboard integration  
- 📄 Post management (Create, Edit, Delete)  
- 📂 Data display via cards  
- 🔍 Detailed drawer view  

---

### 🔹 Website Preview
<img width="1723" height="822" alt="Screenshot 2026-05-02 162047" src="https://github.com/user-attachments/assets/e99d3595-1d1f-4593-863d-f369412246c4" />


👉 Live Link:  
https://potential-memory-5gx7xj777rjgcxxg-5175.app.github.dev/

---

## 📌 BUSINESS IMPACT

- 📊 Helps policymakers plan economic growth  
- 💼 Identifies high-demand industries  
- 🎯 Supports skill development initiatives  
- 🏙️ Improves urban planning  

---

## ⚠️ CHALLENGES

- Power BI embedding limitations  
- Free version restrictions  
- Dataset merging issues  
- Tool compatibility  

---

## 🚀 RECOMMENDATIONS

- Support service-based industries  
- Promote hospitality & tech sectors  
- Encourage skill development programs  
- Expand industries in suburban regions  

---

## 🛠️ TOOLS USED

- Python (Jupyter Notebook)  
- Power BI  
- Excel  
- React + Vite  
- Supabase  
- Clerk  

---

## 👥 TEAM

Group 4 – INFT6900  
University of Newcastle  

---

## ⭐ FINAL NOTE

This project demonstrates:

- 📊 Data Analytics  
- 🧠 Business Insight Generation  
- 🌍 Spatial Data Analysis  
- 🌐 Full-stack integration  

---

<p align="center">
  💼 Open to roles: Data Analyst | Business Analyst | IT Consultant
</p>
