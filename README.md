# Airbnb NYC 2019 Analysis Dashboard – Tableau Project

This project presents a comprehensive Tableau dashboard built to analyze Airbnb listings across New York City using the **AB_NYC_2019 dataset**. It explores host activity, pricing, demand, and review trends across neighborhoods, helping uncover insights for both travelers and property owners.

---

## Dataset

- **Source**: Inside Airbnb (Kaggle: AB_NYC_2019.csv)
- **Rows**: 48,000+ listings
- **Key Columns**: 
  - `name`, `host_name`, `neighbourhood_group`, `neighbourhood`, `latitude`, `longitude`
  - `room_type`, `price`, `minimum_nights`, `number_of_reviews`, `reviews_per_month`
  - `availability_365`, `last_review`

---

## Dashboard Highlights

Built in **Tableau**, the dashboard includes:

-  **Bookings by Neighborhood Group and Room Type**
-  **Average Price by Neighborhood & Room Type**
-  **Reviews Per Month across Room Types**
-  **Top Hosts by Total Reviews**
-  **Neighborhood-level Pricing Map**
-  **Total Reviews by Year**
-  **Monthly Booking Trends**

---

## Key Analyses & Insights

### 1. Neighborhood Focus: Manhattan
- Manhattan has the **highest concentration of listings** and **100% of total analysis in this filtered view**
- Top neighborhoods for pricing: **Tribeca ($490)**, **Battery Park City**, and **Flatiron District**

### 2. Room Type Trends
- **Shared rooms** had the highest average reviews/month, suggesting budget-conscious users are highly engaged.
- **Entire homes/apartments** are priced higher but have slightly lower engagement.

### 3. Top Hosts
- Hosts like *Alex and Zeena* and *Sonder (NYC)* top the list with the highest review counts.
- These superhosts dominate neighborhoods like Chelsea, Harlem, and Financial District.

### 4. Seasonal Booking Trends
- **Peak booking months**: May to July, with **June being the highest** in total bookings.
- Very few bookings in winter months (especially January–March).

### 5. Pricing Heatmap
- Areas like **Financial District**, **Tribeca**, and **SoHo** reflect **premium pricing**, likely due to location desirability and property type.

---

##  Tools Used

- **Tableau** – Interactive dashboard and data storytelling
- **Excel/CSV** – Dataset transformation and upload
- **Mapbox** – Used for geo-visualizations in NYC

---

## How to Use

1. Download the `.twbx` Tableau dashboard file from this repository
2. Open it using **Tableau Public** or **Tableau Desktop**
3. Interact with slicers (e.g., Neighborhood Group, Room Type) to explore price and review trends

---

##  Potential Extensions

- Integrate **calendar-based pricing trends**
- Add **review sentiment analysis** using NLP
- Predict occupancy or revenue using machine learning in Python

---

