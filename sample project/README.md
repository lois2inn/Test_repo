
# 🚕 Zuber Rides Data Analysis

## 📌 Project Overview

Zuber, a new ride-sharing service launching in **Chicago**, is exploring trends in its historical trip data to understand customer behavior, operational efficiency, and the influence of external factors like weather. This analysis helps uncover **passenger preferences**, optimize **cab deployment**, and make **data-driven decisions** for improved service delivery.

---

## 🎯 Project Objectives

- Identify top-performing cab companies and analyze usage patterns.
- Understand neighborhood-based demand with a focus on high-traffic areas like **O’Hare** and **The Loop**.
- Measure the impact of **weather conditions** on trip frequency and duration.
- Evaluate trip trends by **day of week**, **hour**, and **company**.
- Develop actionable insights to support operational and marketing strategies.

---

## 🛠 Project Tools & Technologies

- **SQL** – For data querying, aggregation, and reporting.
- **PostgreSQL** – Database management system for running queries and storing relational data.

---

## 📊 Data Analysis and Recommendations

### ER Diagram

<img src = "Zuber_ERD.png" width=700 />
---

### 📈 Key Findings

1. **Top Performing Cab Company**
   - 📅 **Nov 15–16, 2017**:  
     🥇 *Flash Cab* recorded the **highest number of trips** – a total of **19,558** rides.

2. **Keyword-Based Company Search**
   - 🔍 For companies with names containing *“Yellow”* or *“Blue”*:  
     🥇 *Blue Diamond* had the **most rides** from **Nov 1–7, 2017**, with **6,764** trips.

3. **Comparative Company Performance**
   - 🏁 Comparing *Flash Cab* and *Taxi Affiliation Services* to all other companies for **Nov 1–7, 2017**:  
     🚕 The **"Other"** category (all remaining companies combined) had a **higher total trip volume** than either top company individually or combined.

4. **Popular Neighborhoods**
   - 🗺️ The neighborhoods of **O’Hare** and **The Loop** were identified with `neighborhood_id` values:
     - O'Hare → **ID 63**
     - The Loop → **ID 50**

5. **Weather Conditions Integration**
   - 🌦️ Each **hourly ride** was tagged with a designated **weather condition**, starting from a **"Good"** baseline and adjusted accordingly.

6. **Specific Trip Pattern Analysis**
   - 🧭 A filtered view was created to analyze **Saturday rides** that:
     - **Started** in **The Loop**
     - **Ended** at **O’Hare**
     - Included columns for: `Start Time`, `Weather Conditions`, and `Trip Duration`

---

### ✅ Recommendations

- **Company Promotions**: Focus on understanding what makes *Flash Cab* successful on peak days and use those insights for promoting underperforming companies.
- **Keyword Branding**: Names like *Blue Diamond* suggest customer affinity for specific branding styles—potentially leverage this in new cab partnerships or naming strategies.
- **Targeted Weekend Service**: Increase cab availability on **Saturdays** in **The Loop** targeting travelers headed to **O’Hare**—a common airport route.
- **Weather-Aware Scheduling**: Monitor weather forecasts to proactively manage fleet distribution during adverse conditions to minimize trip delays.
- **Neighborhood-Based Marketing**: Promote services and discounts in neighborhoods like **The Loop**, where customer pickup activity is high.

---
