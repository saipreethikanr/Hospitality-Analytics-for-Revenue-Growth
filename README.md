# 🏨 Hospitality Domain Dashboard - Power BI

## 📊 Overview

This project features a comprehensive **Power BI Dashboard** analyzing key performance metrics across multiple hotel properties under the **Atliq brand**. The dashboards offer in-depth insights into:

- **Revenue performance**
- **Occupancy rates**
- **ADR (Average Daily Rate)**
- **Customer ratings**

Data is segmented by property and city with weekly trends, enabling better operational decisions and optimization of hotel services.

---

## 📁 About the Dataset

The project uses **five CSV files** representing:

- **Date information**
- **Hotel details**
- **Room categories**
- **Aggregated bookings**
- **Individual bookings**

Key columns include:

- Room types  
- Booking & cancellation details  
- Guest counts  
- Revenue figures  
- Rating scores  

Together, they enable a holistic analysis of **customer behavior** and **hotel operations**.

---

## 🛠️ Tools & Technologies Used

| Tool         | Purpose                              |
|--------------|---------------------------------------|
| **Excel**    | Initial data loading & pre-cleaning   |
| **Power Query** | Data cleaning, null handling, transformation |
| **Power BI** | Visualization, interactive dashboard  |
| **DAX**      | Calculated measures & data modeling   |

---

## 🧹 Data Cleaning & Modeling Steps

1. Loaded Excel/CSV data into Power BI.
2. Cleaned data using **Power Query**:
   - Removed duplicates
   - Handled missing values
   - Corrected column types & formats
3. Established relationships between tables for a unified data model.
4. Created a dedicated **"Key Measures" table** to calculate KPIs like:
   - Revenue
   - Occupancy
   - ADR
   - Realisation %
   - Cancellation %

---

## 📈 Key Insights

### 🔢 Overall Metrics
- **Total Revenue**: ₹1,688 million  
- **Average RevPAR**: ₹7,337  
- **Average Occupancy**: 58%  
- **Average ADR**: ₹12,696  
- **Realisation %**: 70%  
- **Cancellation %**: 24%-26%

### ⭐ Top Performing Properties
| Property               | City     | Revenue | ADR     | Occupancy |
|------------------------|----------|---------|---------|-----------|
| Atliq Exotica          | Mumbai   | ₹117M   | ₹16,141 | 66%       |
| Atliq Palace           | Mumbai   | ₹100M   | ₹16,016 | 66%       |

### 📉 Lowest Performing Properties
| Property               | City       | Revenue | ADR     | Occupancy |
|------------------------|------------|---------|---------|-----------|
| Atliq Exotica          | Hyderabad  | ₹47M    | ₹9,111  | 45%       |
| Atliq Bay              | Mumbai     | ₹51M    | ₹15,167 | 45%       |

---

## 🚀 How to Use

1. **Download Power BI Desktop**  
   [Power BI Official Site](https://powerbi.microsoft.com/)

2. **Clone the Repository**  
   ```bash
   git clone https://github.com/saipreethikanr/hospitality-powerbi-dashboard.git
   ```

3. **Open the Dashboard**  
   - Locate and open `Revenue Insights in the Hospitality Domain.pbix` in Power BI Desktop.

4. **Explore & Interact**  
   - Use slicers, filters, and visualizations to gain actionable insights.

---

## 📌 Future Enhancements

- Add forecasting using time series models  
- Integrate real-time booking APIs  
- Expand analysis to cover food & beverage metrics

---


