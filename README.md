**Project Title :**
**Ola Ride Data Analysis – Customer Behavior, Operational Insights & Ride Performance**
---------------------------------------------------------------------------------------------------------------------------
## 📊 Dashboard Snapshot:
<p align="center">
  <img src="./Dashboard SS/Ola Overall.png" width="700" alt="Summary Dashboard">
  <br><i> 1. Ola Overall Dashboard </i>
</p>
<p align="center">
  <img src="./Dashboard SS/Ola Vehicle.png" width="700" alt="Summary Dashboard">
  <br><i> 2. Ola Vehicle Type Dashboard </i>
</p>
<p align="center">
  <img src="./Dashboard SS/Ola Revenue.png" width="700" alt="Summary Dashboard">
  <br><i> 3. Ola Revenue Dashboard </i>
</p>
<p align="center">
  <img src="./Dashboard SS/Ola Cancellation.png" width="700" alt="Summary Dashboard">
  <br><i> 4. Ola Cancellation Dashboard </i>
</p>
<p align="center">
  <img src="./Dashboard SS/Ola Rating.png" width="700" alt="Summary Dashboard">
  <br><i> 5. Ola Ratings Dashboard </i>
</p>
<p align="center">
  <img src="./Dashboard SS/Ola Extra research.png" width="700" alt="Summary Dashboard">
  <br><i> 5. Ola Extra Research Dashboard </i>
</p>
---------------------------------------------------------------------------------------------------------------------------

**🧠 Objective :**

To analyze Ola ride data for the month of July to uncover insights into ride performance, customer behavior, payment preferences, vehicle usage patterns, and potential operational inefficiencies like cancellations and incomplete rides.

---------------------------------------------------------------------------------------------------------------------------
**📁 Data Source :**

**Excel File :** Ola July Data.xlsx

Loaded and processed using: Python (Pandas) and Power BI

---------------------------------------------------------------------------------------------------------------------------
**🛠️ Tools & Technologies Used :**

**Python** (Pandas)  Jupyter Notebook

**Power BI** (for data visualization and dashboarding)

**Excel** (for raw data cleaning and inspection)

---------------------------------------------------------------------------------------------------------------------------
**📊 Key Analysis Performed:**

**Ride Completion Status:**

**Total Rides :** Calculated using len(Data)

**Successful Rides :** Filtered where Booking_Status == 'Success'

**Incomplete Rides :** Grouped and analyzed by Incomplete_Rides_Reason

**Canceled rides analyzed by both driver and customer.**

**Customer Behavior :**

Top 5 customers based on total Booking_Value

Distribution of Payment_Method (UPI, Card, Cash, etc.)

Average customer rating per vehicle type

**Operational Insights :**

Total Booking Value of successful rides

Average ride distance and rating by vehicle type

**Vehicle Usage :**

Count of rides per vehicle type

Average distance and rating for each vehicle type

Most preferred vehicle types by customers

---------------------------------------------------------------------------------------------------------------------------
**📈 Visualizations Created in Power BI :**

**Pie chart of :** Booking_Status breakdown And Cancelled Rides by Customer & Drivers

**Bar charts for :**

Revenue by Payment Method

Total Ride Distance by Day

Ride Volume Overtime

**Filters for :** date.

---------------------------------------------------------------------------------------------------------------------------**💡 Key Insights :**

Prime Plus had the highest customer ratings.

Cash emerged as a widely used payment method.

The most common reason for incomplete rides was Customer Demand.

Customers booking Auto had the shortest ride distances on average.

---------------------------------------------------------------------------------------------------------------------------**✅ Conclusion :**

The analysis provided insights into ride trends, customer satisfaction, and operational issues. These findings can help optimize vehicle allocation, reduce cancellations, and improve customer experience. The interactive Power BI dashboard makes it easier for stakeholders to explore data dynamically.

