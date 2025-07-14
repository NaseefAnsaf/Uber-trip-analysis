# 🚖 Uber Trip Analysis – Power BI Dashboard

## 📌 Project Summary

The **Uber Trip Analysis Project** leverages Power BI to transform raw trip data into actionable business insights. The analysis covers **104,000 trips**, generating **$1.6 million in revenue**, and includes three interactive dashboards focused on bookings, revenue, trip efficiency, and temporal demand patterns.

---

## 🎯 Objectives

- Analyze trip bookings, revenue generation, and trip efficiency.
- Identify time and location-based trends to optimize resource allocation.
- Empower stakeholders with interactive, self-service dashboards.
- Improve decision-making with real-time visual insights.
- Enhance customer satisfaction and operational agility.

---

## 📊 Dashboards Overview

### 🔹 Dashboard 1: Overview Analysis
**Key KPIs:**
- Total Bookings: `104,000`
- Total Revenue: `$1.6M`
- Average Booking Value: `$15`
- Total Trip Distance: `349,000 miles`
- Average Trip Time: `16 mins`
- Average Trip Distance: `3 miles`

**Highlights:**
- 🟢 **Google Pay** leads digital payment (70.7% of revenue).
- 🌙 Night trips contribute 62.7% of revenue.
- 🚘 **UberX** dominates in bookings and distance.

**Vehicle Type Summary Table:**

| Vehicle Type   | Bookings | Revenue   | Avg Fare | Distance (mi) |
|----------------|----------|-----------|----------|----------------|
| UberX          | 38,744   | $583,880  | $15.00   | 131,496        |
| Uber Black     | 16,710   | $250,192  | $15.00   | 56,149         |
| Uber Comfort   | 17,078   | $253,995  | $15.00   | 56,790         |
| UberXL         | 16,698   | $249,424  | $15.00   | 55,720         |
| Uber Green     | 14,498   | $216,181  | $15.00   | 48,778         |

**Location-Based Insights:**
- 🔺 **Top Pickup:** Penn Station / Madison Square West
- 🔻 **Top Drop-off:** Upper East Side North
- 🚗 **Farthest Trip:** 144.1 miles (Lower East Side → Crown Heights North)

---

### 🔹 Dashboard 2: Time Analysis
**Visualizations:**
- ⏰ **Area Chart by Pickup Time (10-min intervals)**
- 📅 **Line Chart by Day of Week**
- 🔥 **Heatmap by Hour & Day**

**Demand Patterns:**
- 🌄 **Morning Peak:** 7–9 AM ($9K–$16K/hour)
- 🌆 **Evening Peak:** 5–7 PM ($21K–$23K/hour)
- 🌙 **Off-Peak:** 2–4 AM ($1K–$2K/hour)
- 📈 **Weekend traffic** exceeds weekday demand by up to 30%

---

### 🔹 Dashboard 3: Details Tab
**Features:**
- 🧾 Grid view of all trip details (Vehicle, Payment, Distance, etc.)
- 🔎 Drill-through from charts for granular insights
- 🔁 Toggle bookmark for full/filtered data view

---

## 🧠 Key Insights

- **Digital Wallet Adoption:** Google Pay and Uber Pay account for 99.2% of transactions.
- **Revenue Skew:** Night rides drive majority of earnings.
- **Location Density:** A few hubs contribute disproportionate trip volumes.
- **Peak Demand:** Concentrated around 7–9 AM & 5–7 PM.
- **Trip Uniformity:** All vehicle types maintain $15 average fare.

---

## ✅ Recommendations

- 🔄 **Optimize Driver Scheduling**: Align driver shifts with peak hours.
- 💸 **Promote Digital Wallets**: Incentivize cash users to switch.
- 🚕 **Prioritize UberX**: Allocate more vehicles to high-demand corridors.
- 💡 **Apply Surge Pricing**: Target evening and weekend peaks.
- 🌍 **Explore Intercity Fares**: Consider premium pricing for long-distance rides.

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development, DAX modeling
- **Power Query** – Data transformation
- **Power Automate** – CSV export automation
- **Bookmarks & Tooltips** – Enhanced user experience
- **Dynamic Measures & Titles** – Flexible visuals using disconnected tables

---
