# Uber-Data-Analysis
## 📊 Overview
This project presents an interactive **Uber Trips Analytics Dashboard** built in Tableau. It provides insights into booking trends, ride distances, revenue patterns, and customer behavior over time.

The dashboard is designed to help stakeholders:
- Understand ride demand patterns  
- Analyze revenue performance  
- Identify peak booking times  
- Explore distance-based pricing behavior  

---

## 📁 Dataset Description

**File Name:** `Uber.csv`  

The dataset contains ride-level transactional data for Uber trips.

### Key Columns

| Column Name        | Description |
|-------------------|------------|
| Booking ID        | Unique identifier for each trip |
| Pickup Date       | Date of the ride |
| Pickup Time       | Time of the ride |
| Pickup Location   | Location where ride started |
| Drop Location     | Destination of the ride |
| Ride Distance     | Distance traveled (in km) |
| Booking Value     | Total fare charged |
| Payment Type      | Mode of payment |
| Ride Status       | Completed or Cancelled |

---

## 🎯 Dashboard Features

### 🔹 KPI Metrics
- **Total Bookings:** 148.77K  
- **Total Revenue:** 51.85M  
- **Average Booking Value:** 508.30  
- **Average Ride Distance:** 24.64 km  

---

### 🔹 Time-Based Analysis

#### Total Trips by Month
- Consistent ride demand throughout the year  
- Slight peaks in mid-year and year-end  

#### Revenue by Month
- Closely follows booking trends  
- Indicates stable revenue generation  

#### Total Bookings by Day
- Even distribution across weekdays  
- Slight increase on weekends  

#### Total Bookings by Hour
- Peak: **5 PM – 8 PM**  
- Lowest: Early morning hours  

---

### 🔹 Distance & Pricing Insights

#### Average Fare by Distance Bucket
- 0–3 km  
- 3–7 km  
- 7–15 km  
- 15+ km  
- Slight fare increase with distance  

#### Trip Distance Distribution
- Most trips fall between **5–20 km**  

#### Fare vs Distance
- Positive correlation between fare and distance  
- Some variability suggests dynamic pricing  

---

### 🔹 Location Insights

#### Revenue by Pickup Location
- Identifies high-performing areas  
- Helps optimize driver allocation  

---

## 🎛 Filters

- **Date Range Filter** – Analyze custom time periods  
- **Pickup Location Filter** – Drill into specific areas  

---

## 🛠 Tools Used

- Tableau  
- CSV Dataset  
- Data Cleaning (pre-processing step)  

---

## 📌 Key Insights

- Demand is stable throughout the year  
- Evening hours have the highest bookings  
- Majority of rides are short to medium distance  
- Revenue strongly correlates with bookings  
- Pricing is relatively consistent across distances  

---

## 🚀 How to Use

1. Open Tableau Desktop  
2. Load `Uber.csv`  
3. Open the Tableau workbook (`.twb` or `.twbx`)  
4. Use filters to explore insights  

---

## 📷 Dashboard Preview

_Add your Tableau dashboard screenshot here_

---

## 🔮 Future Improvements

- Surge pricing analysis  
- Driver performance metrics  
- Real-time data integration  
- Demand forecasting models  

---

## 📄 License

For educational and analytical use only  

---
