# Blue Bikes Case Study: Round-Trips, Seasons & Demographics

This interactive Tableau dashboard explores key patterns in Boston’s Blue Bikes system, focusing on round-trip behavior, seasonal trends, and demographic insights. By analyzing trip duration, station-level usage, and temporal-demographic activity, this case study provides actionable recommendations for operational efficiency and user engagement.

 **Dashboard Link**:  https://public.tableau.com/app/profile/vanshika.gupta5390/viz/BlueBike_17498459431790/Dashboard1?publish=yes
 **Business Use Case**: Operational planning, marketing strategy, demographic outreach

---

## 1. Business Question

**How do round-trip patterns vary across stations during commute times, how does the average trip duration fluctuate across seasons based on user type, and how do trip volumes differ by gender and age group across hours of the day?**

###  Why This Matters  
This question integrates spatial, seasonal, and demographic factors—critical for system optimization and strategic decision-making.  
- **Round-trip trends** help optimize bike redistribution and station placement.  
- **Seasonal trip duration by user type** supports targeted promotions and operational readiness.  
- **Demographic-based trip volumes** inform inclusive outreach and time-based operations.

---

## 2.  Tableau Dashboard

![Screenshot 2025-06-09 133224](https://github.com/user-attachments/assets/64dce780-ab57-4869-bd12-1856efb8d6d7)


### Key Features

| Visualization              |                             Purpose                           |
|----------------------------|---------------------------------------------------------------|
| **Interactive Map**        | Displays round-trip patterns during commute hours by station  |
| **Seasonal Bar Chart**     | Compares average trip durations across seasons and user types |
| **Demographic Line Chart** | Shows hourly usage trends by gender and age group             |

---

## 3.  Visualizations Overview

### 1. **Round Trip Patterns Across Stations During Commute Times**
- **Variables:** Start station location, trip type, commute time  
- **Chart Type:** Geospatial map  
- **Insight:** Identifies high-demand round-trip hubs, informing bike redistribution during morning/evening commute hours.

### 2. **Average Trip Duration by Season for Each User Type**
- **Variables:** Season, trip duration, user type (Subscriber or Customer)  
- **Chart Type:** Bar chart  
- **Insight:** Highlights recreational vs. utilitarian usage trends; summer trips are notably longer, especially for Subscribers.

### 3. **Trip Volumes by Gender and Age Group Across Hours of the Day**
- **Variables:** Hour, gender, age group, trip count  
- **Chart Type:** Line chart  
- **Insight:** Peak usage among 25–35 year-olds around 8 AM and 5 PM suggests commute-based patterns; under-25 usage peaks mid-day.

---

## 4.  Operational Insights

- **High-Demand Stations:** Central Boston stations see most round trips during evening commutes—ideal for station rebalancing.
- **Trip Duration Peaks in Summer:** Subscribers take longer trips in summer (avg. ~1300 secs), signaling a potential for seasonal pricing or events.
- **Demographic Time Use:** 25–35 year-olds dominate usage, especially at commute times. Female users under 35 peak sharply at 8 AM and 5 PM.

---

## 5.  Recommendations

 **Optimize Bike Distribution**  
Reallocate bikes to high-demand stations during commute windows based on round-trip map insights.

 **Targeted Promotions**  
Launch summer campaigns focused on subscribers and long-distance users.

 **Demographic Outreach**  
Increase engagement among underrepresented groups (e.g., older riders) and tailor communication by age/time-of-day usage.

 **Data-Driven Adjustments**  
Continue monitoring trip trends seasonally and demographically to guide long-term planning.
