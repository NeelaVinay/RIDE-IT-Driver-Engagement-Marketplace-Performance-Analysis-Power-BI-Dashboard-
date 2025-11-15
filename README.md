# 🚗 RIDE IT — Driver Engagement & Marketplace Performance Analysis (Power BI Dashboard)

## 📌 Project Overview
This Power BI dashboard analyzes driver engagement, booking behavior, and operational performance for **RIDE IT**, a multi-service mobility platform offering ride-hailing, e-scooters, e-bikes, e-Vespas, and car-sharing services.  
Using two datasets—**rideit_drivers** and **rideit_drivers_activity**—the project focuses on identifying:

- What drives higher engagement  
- Which segments perform well or poorly  
- What operational gaps exist  
- How to improve platform reliability & driver satisfaction  

This capstone project consolidates driver-level and activity-level data into a unified view, enabling stakeholder-ready, data-driven decisions.

---

## 📂 Data Sources
### **rideit_drivers.csv**
Driver-level attributes such as:
- Driver Rating  
- Gold-Level Achievements  
- Registration Date  
- Marketing Opt-In Status  
- Country of Operation  
- Service Type (TAXI / PHV)

### **rideit_drivers_activity.csv**
Daily operational and engagement metrics:
- Offers Received  
- Bookings Accepted  
- Passenger / Driver Cancellations  
- Completed Rides  
- Active Operating Dates  

In addition to raw fields, **derived engagement metrics** were engineered during analysis to quantify driver behavior more accurately.

---

## 📊 Key Metrics Defined
- **Acceptance Rate**  
- **Completion Rate** 
- **Cancellation Ratio** 
- **Activity Frequency** 
- **Engagement Score**  
  A composite KPI combining activity frequency, acceptance, completion, and cancellation behavior to quantify overall driver engagement and reliability.

---

## 🔍 Insights (Executive Summary)
- High-rated and gold-level drivers demonstrate **stronger and more consistent engagement**.  
- **PHV drivers outperform TAXI drivers** across acceptance, completion, and reliability metrics.  
- Drivers opted into marketing communications show **higher platform activity** and better retention.  
- High cancellation behavior is a strong indicator of **low engagement and unstable performance**.  
- Country-level differences indicate **operational inefficiencies** in certain markets.  
- New drivers display fluctuating engagement → improved onboarding required.

---

## 🚀 Recommendations
1. **Introduce a Driver Engagement Index (DEI)** to track driver performance longitudinally.  
2. **Deploy targeted nudges** to improve acceptance and reduce cancellations.  
3. Implement **tier-based rewards** (Gold → Platinum → Elite) to improve consistency.  
4. **Optimize dispatching** in low-acceptance, high-cancellation regions.  
5. **Enhance onboarding** with training, tutorials, and guided first-week support.

---

## 🛠️ Tools & Skills
- Power BI Desktop  
- Power Query  
- DAX  
- Data Modeling  
- KPI Engineering  

---

## 📥 How to Use
Download the `.pbix` file → Open in **Power BI Desktop** → Explore dashboard visuals using slicers and filters.

---

## 👤 Author
**Neela Vinay**  
Data Analyst | Power BI Developer 

⭐ If this project helped you, please consider giving the repository a star!
