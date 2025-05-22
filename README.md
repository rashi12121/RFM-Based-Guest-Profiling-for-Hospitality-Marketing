# RFM-Based-Guest-Profiling-for-Hospitality-Marketing
## 📝 Overview / Objective

The purpose of this project is to help **Green Valley Resort** better understand its guest base by segmenting guests based on **age**, **guest tiers**, and **average booking amount**. The final dashboard enables resort management to make data-driven decisions to enhance guest experience and loyalty through targeted marketing and personalized services.

---

## 📊 Dataset Description

- **File Name**: `GreenValley - Data.csv`
- **Source**: Provided by Green Valley Resort management (simulated for project use)
- **Key Variables**:
  - `Guest ID`
  - `Guest Name`
  - `Age`
  - `Gender`
  - `Guest Tier` (Gold, Silver, Bronze)
  - `Booking Frequency`
  - `Booking Amount`

---

## 🧹 Data Cleaning & Preprocessing

- Removed duplicate Guest IDs if any
- Ensured consistent formatting for numerical columns (`Booking Amount`, `Frequency`)
- Created **Age Groups**:
  - 21–30 → **Young**
  - 31–45 → **Middle Age**
- Verified no nulls in primary analysis columns

---

## 🔍 Exploratory Data Analysis (EDA)

- Distribution of guest age and spending
- Booking frequency histogram
- Guest tier breakdown by frequency and amount
- Age group segmentation by revenue contribution

---

## 📈 Visualizations

**Tableau Sheets:**

1. **Total Booking Amount** – ₹ total of all bookings
2. **Number of Bookings** – Total count of bookings
3. **Unique Guest** – Count of distinct guest IDs
4. **Average Spending** – Avg. spend per guest
5. **Tree Map** – Visual segmentation by Tier and Booking Amount
6. **Scatter Plot** – Booking Frequency vs. Amount by Tier
7. **Pie Chart** – Share of booking amounts by Age Group
8. **Guest Table** – Table of individual guests and key metrics

---

## 📊 Dashboard

### Title: `Guest Segmentation | RFM Analysis`

- **Background**: `#023e8a`
- **Shading**: `#caf0f8`
- **Filters**:
  - Age (Group)
  - Gender
  - Applied to all worksheets using this data source

🖼️ ![Dashboard](https://github.com/rashi12121/RFM-Based-Guest-Profiling-for-Hospitality-Marketing/blob/main/_Green%20Vally%20Resort%20Dashboard.png)

---

## 🧠 Insights & Key Findings

- **Gold-tier guests** contribute the highest revenue per booking.
- **Young guests** have higher booking frequency but lower average amount.
- **Middle Age group** contributes more in total booking amount.
- **Scatter plot** indicates a positive correlation between frequency and booking amount in higher tiers.

---

## 💡 Recommendations

- Design exclusive promotions for **Middle Age group** to retain loyalty.
- Offer tier upgrade incentives to **Silver and Bronze guests** with high frequency.
- Create bundled packages for **Young guests** to increase per-booking spend.

---

## 🛠️ Tools & Technologies Used

- 📊 **Tableau Public** – For data visualization and dashboard creation
- 🐼 **Pandas** (for initial inspection if needed)
- 📁 **CSV Files** – For raw data
