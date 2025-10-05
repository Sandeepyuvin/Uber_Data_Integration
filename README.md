# 🚗 Uber Traffic Fare Analysis

### 📘 Project Overview  
This project explores how **traffic congestion**, **weather**, and **city events** affect **Uber ride fares** and **trip durations**.  
By integrating multiple real-world datasets, it identifies how conditions like heavy traffic or rain influence dynamic pricing and travel time.

---

## 🧩 Datasets Used  
- **Uber Rides Data** – Trip start/end time, distance, fare, duration  
- **Traffic Data** – Congestion index, average speed  
- **Weather Data** – Temperature, precipitation, humidity, wind speed  
- **Events Data** – Sports, concerts, holidays affecting local traffic  

---

## ⚙️ Steps Performed  
1. Imported and cleaned all datasets.  
2. Merged them using **timestamp-based integration** (nearest time match).  
3. Removed missing or incorrect values.  
4. Fixed negative fares and durations using data clipping.  
5. Created features for **traffic level** and **hourly patterns**.  
6. Visualized relationships between congestion, fare, and duration.  

---

## 📊 Visual Insights  
- **Higher congestion = higher fares and longer trips**  
- **Peak hours (8–10 AM, 5–8 PM)** show max surge and slow travel times  
- **Rain and events** significantly impact traffic and fare rates  

---

## ✅ Key Findings  
- Traffic and weather heavily influence Uber’s fare prices.  
- Dynamic pricing responds directly to congestion and demand.  
- Integrated data helps understand and predict Uber’s surge behavior.  

