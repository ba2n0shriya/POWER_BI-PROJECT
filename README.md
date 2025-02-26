# POWER_BI-PROJECT
Here's an overview of your **Airline Performance Analysis using Power BI** project:

### **Project Title**:  
**Airline Performance Analysis using Power BI**  

### **Problem Statement**:  
The airline industry involves complex daily operations such as flight scheduling, passenger management, and ticket booking. Analyzing and managing this data efficiently is crucial for improving operational performance, customer satisfaction, and strategic decision-making. This project aims to streamline and visualize airline operations using Power BI to derive meaningful insights.

---

### **Project Objectives:**
- Analyze and visualize airline data for better insights.  
- Improve decision-making in flight operations, passenger management, and ticketing.  
- Utilize Power BI features such as Power Query, DAX, and interactive dashboards.  

---

### **Project Tasks and Implementation Steps:**

#### **1. Data Extraction and Transformation **
- Import CSV datasets into Power BI.  
- Clean the data by removing duplicates, handling missing values, and formatting columns.  

#### **2. Creating Custom & Conditional Columns**
- Add a **Conditional Column** to classify flights as:
  - **"Best"** (On Time).  
  - **"To Be Improved"** (All other statuses).  

#### **3. Column from Examples & Replacing Values )**
- Use **"Column from Examples"** to extract numeric values from FlightNumber.  
- Standardize Status values (e.g., "On Time" → "On-Time").  

#### **4. Merge Queries and Columns **
- **Merge Flight & Passenger Data** based on FlightID to unify datasets.  
- **Combine SeatNumber & PassengerID** to create unique passenger identifiers.  

#### **5. Create Relationships **
- Establish relationships between datasets using **FlightID** as the key.  
- Define cardinality between tables (One-to-Many relationships).  

#### **6. DAX Calculations **
- Calculate:
  - **Total number of passengers** for a specific flight (e.g., FL1276).  
  - **Total number of tickets booked** across all flights.  
  - **Filtered Table** showing only “Best” flights using DAX.  

#### **7. Visualizations **
- **Multi-card chart** → Shows number of passengers & flights per airline.  
- **Bar chart** → Compares passengers per airline.  
- **Donut chart** → Represents ticket booking status distribution.  

#### **8. Advanced Visualizations **
- **Decomposition Tree** → Breakdown of flights based on airlines & destinations.  
- **Key Influencer Visual** → Q&A feature to visualize booking statuses.  

#### **9. Interactive Features **
- **Slicers** → Filter by Destination, Total Passengers, and Total Flights.  
- **Bookmarks** → Save different report views for quick access.  
- **Drill-through** → Navigate from an airline summary to detailed destinations & flights.  

#### **10. Final Report & Deployment **
- **Create a Power BI workspace “Airline”** for report hosting.  
- **Role-Level Security (RLS)** → Restrict access to **only Airline A’s** data for a specific user.  
- **Schedule Refresh** → Configure data to update daily at **5 PM**.  

---

### ** Outcome:**
- A **Power BI Dashboard** providing key insights into airline performance.  
- Improved **decision-making** for airline management teams.  
- Interactive features for **dynamic analysis** of flights, passengers, and bookings.  

---
