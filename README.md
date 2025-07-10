# Rapido-Bookings-Data-Analysis
## Project-Objective
To analyze large-scale ride data from Rapido in order to identify key trends in revenue, vehicle usage, customer behavior, and cancellations—using SQL and Power BI to enable data-driven decision-making and improve business performance. 
## SQL Questions:

1. Retrieve all successful bookings.

2. Find the average ride distance for each vehicle type.

3. Get the total number of canceled rides by customers.

4. List the top 5 customers who booked the highest number of rides.

5. Get the number of rides canceled by drivers due to personal and car-related issues.

6. Find the maximum and minimum driver ratings for Prime Sedan bookings.

7. Retrieve all rides where payment was made using UPI.

8. Find the average customer rating per vehicle type.

9. Calculate the total booking value of rides completed successfully.

10. List all incomplete rides along with the reason.

##  Power BI Questions:

1.Ride Volume Over Time.
2.Booking Status Breakdown.

3.Top 5 Vehicle Types by Ride Distance.

4.Average Customer Ratings by Vehicle Type.

5.Canceled Rides Reasons.

6.Revenue by Payment Method.

7.Top 5 Customers by Total Booking Value.

8.Ride Distance Distribution Per Day.

9.Driver Ratings Distribution.

10.Customer vs Driver Ratings.

##  Tools & Technologies

- **SQL** – Data cleaning, filtering, aggregation
- **Excel** – Initial data preprocessing
- **Power BI** – Interactive dashboard creation
- **Power Query** – Data loading and shaping

  ##  Project Process:

### 1. 📥 Data Collection
- Collected over **100,000+ ride records** for the month of **July 2024**.
- Dataset included:  
  - Booking status  
  - Timestamps  
  - Booking value  
  - Vehicle types  
  - User feedback  

---

### 2. 🧹 Data Cleaning & Transformation
- Used **Excel** and **Power Query** to:
  - Remove null and duplicate entries  
  - Standardize date formats and booking status values  
  - Convert unstructured fields into clean, analysis-ready tables  

---

### 3. 🔗 Data Modeling in Power BI
- Imported the cleaned dataset into **Power BI Desktop**
- Created relationships between key fields:
  - `Ride_Date`, `Vehicle_Type`, `Booking_Status`
- Designed a **data model** supporting:
  - Time-series analysis  
  - Categorical segmentation  
  - Cross-filtered visuals  

---

### 4. 📊 Dashboard Development
Built an **interactive dashboard** in Power BI with the following visuals:

- **Pie Chart:**  
  - Booking Status Breakdown (Success, Canceled by Driver, Canceled by Customer, Driver Not Found)

- **Line Chart:**  
  - Daily Ride Volume Trend (*Ride_Volume_Over_Time*)

- **KPI Cards:**  
  - `Total Bookings:` **103,024**  
  - `Total Booking Value:` **35M**

- **Date Slicer:**  
  - Interactive filter (from `01-07-2024` to `31-07-2024`)

- Applied a custom **yellow & black theme** to reflect **Rapido branding** and maintain visual consistency

---

### 5. 💡 Insight Generation
- 📌 **62% of bookings were successful**, while the rest were canceled or failed  
- 📉 **Observed fluctuations in daily ride volume**, helping identify peak demand periods  
- 📈 Delivered actionable insights to help stakeholders improve:
  - **Driver allocation**
  - **Cancellation management**
  - **Customer experience**

---
##  Dashboard Preview

![Rapido Dashboard](https://github.com/HariMakineedi/Rapido-Bookings-Data-Analysis/blob/main/Rapido-Dashboard.png)

##  Conclusion

This project successfully demonstrated the power of combining **SQL**, **Excel**, and **Power BI** for end-to-end data analysis. By examining over 100,000 Rapido ride records, we identified key trends in booking success, cancellations, and revenue patterns. The interactive dashboard empowers stakeholders to make data-driven decisions, improve operational efficiency, and enhance user satisfaction. This analysis showcases how real-time data insights can support business growth and strategic planning.




