# 🕵️‍♂️ Crime Analysis and Detection using K-Means Clustering

## 📌 Overview
This project focuses on analyzing and detecting crime patterns using the **K-Means Clustering Algorithm**. By clustering historical crime data, we aim to uncover **crime hotspots** and **trends** that can assist law enforcement and city planners in better decision-making.

---

## 🚀 Key Features
- 📊 Clusters crime data based on spatial coordinates and crime attributes  
- 🧭 Detects high-risk areas and potential crime zones  
- 🗺️ Interactive visualizations using geographic heatmaps and cluster plots  
- 🧮 Uses unsupervised learning with K-Means Clustering  
- 🧹 Comprehensive data cleaning and normalization pipeline  
- 📈 Exploratory Data Analysis (EDA) with crime trends and patterns  

---

## 🛠️ Technologies Used

| Category         | Tools Used                                 |
|------------------|--------------------------------------------|
| Programming      | Python                                     |
| Data Handling    | Pandas, NumPy                              |
| Visualization    | Matplotlib, Seaborn, Folium                |
| Machine Learning | Scikit-learn (KMeans)                      |
| Mapping          | Folium, Plotly, GeoPandas *(optional)*     |

---

## 🔍 How It Works

### 📥 1. Load the Dataset
- Import real or simulated crime datasets (CSV or XLSX format)

### 🧹 2. Data Preprocessing
- Handle missing or inconsistent entries  
- Normalize features (especially latitude and longitude)  
- Convert date/time formats for analysis  

### 📍 3. Feature Selection
Key features used in clustering:
- `Latitude`, `Longitude`  
- `Crime Type` (One-hot encoded or mapped)  
- `Time or Day of Crime` *(Optional)*  

### 📊 4. Apply K-Means Clustering
- Group similar crimes based on spatial and temporal features

### 🗺️ 5. Visualize the Results
- Scatter plots, heatmaps, and geo-maps to display:
  - Crime hotspots  
  - Cluster centers  
  - Crime type distribution by region  

---

## 📂 Dataset Description

The dataset contains real or synthetic data with the following fields:

| Field Name   | Description                                |
|--------------|--------------------------------------------|
| Case ID      | Unique identifier for each record          |
| Date/Time    | Timestamp of when the crime occurred       |
| Latitude     | Y-coordinate (geographic)                  |
| Longitude    | X-coordinate (geographic)                  |
| Crime Type   | Nature of the crime (e.g., theft, assault) |
| Location     | Address or neighborhood *(optional)*       |

> 💡 *Optionally enriched with socio-economic or population density data for deeper insights.*

---

## 📸 Results & Visualizations

Below are visual outputs of the clustering and analysis:

![a1](https://github.com/user-attachments/assets/cdff5d48-fffe-4d2b-a199-447cb3320fa3)  
![a2](https://github.com/user-attachments/assets/9c13956c-a097-4b1f-87b2-19096af7d556)  
![a3](https://github.com/user-attachments/assets/ad2a9622-4158-43ed-b1f8-6a59442c34c4)  
![a4](https://github.com/user-attachments/assets/eb2014da-de72-4e34-995f-4a84973c7fdd)  
![a5](https://github.com/user-attachments/assets/b02baa5a-110f-4314-9408-1ff2d1b32855)  
![a6](https://github.com/user-attachments/assets/11fd0153-1a18-4d6b-9446-cc0cc5088ed0)  
![a7](https://github.com/user-attachments/assets/19b8b7df-7693-40cd-a25c-9b8eef24c96c)  
![a8](https://github.com/user-attachments/assets/9aeb2dd0-d536-4414-b861-797d3c2141c9)  
![a9](https://github.com/user-attachments/assets/e98c5462-1bb2-4291-a3da-d5b38c364a58)  
![a10](https://github.com/user-attachments/assets/8030334f-c013-4394-a32a-f815e1006ee2)  
![a11](https://github.com/user-attachments/assets/807c8a32-e924-4e63-a8bf-345d035d5c94)

---
