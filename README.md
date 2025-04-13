# COMPANY:

# DISCRIPTION

## 📊 Real-Time Power BI Dashboard


This Power BI project showcases a **real-time dashboard** built for business executives to monitor key performance metrics as data flows in. Designed with a focus on **streaming data**, this dashboard enables dynamic and up-to-the-second visibility into revenue performance, units sold, geographical segmentation, and customer demographics. The report is particularly useful for organizations that need **immediate insights** to make fast decisions, such as in sales, retail, or supply chain operations.

The dashboard is built using simulated real-time data streams, making it highly effective even without access to actual live APIs or Azure data streams. It serves as a practical demonstration of **Power BI's live dashboard capabilities**.

---

### 🎯 Objectives

- Build a **live-updating dashboard** using streaming or simulated data.
- Display business metrics like revenue, unit sales, and category performance in **real time**.
- Provide dynamic filtering by geography, category, segment, and year.
- Make the dashboard interactive and visually appealing for stakeholders.

---

### 🧩 Key Features

#### 1. **Live KPI Tile – Revenue Monitoring**
- Shows the real-time revenue for the year 2017.
- Includes a goal reference line ($227.11M) and performance deviation (-47.38%) using KPI visuals.
- This KPI tile turns red when the goal is not met, making it easy to interpret business health instantly.

#### 2. **Units Sold – Real-Time Update**
- Displays the total units sold (71K in 2017) using a card visual.
- Updates automatically as new transaction data is streamed in.

#### 3. **Trends by Manufacturer**
- A line chart illustrating revenue performance over time by manufacturer (Aliqui, Currus, Natura).
- Helps identify long-term trends and spikes in performance.

#### 4. **Category-Wise Insights**
- Another time series chart that segments performance based on customer categories (Mix, Rural, Urban, Youth).
- Useful for demographic or behavioral analysis.

#### 5. **Geographical Analysis**
- A bar chart breaks down revenue contributions by **country** and **customer type** (Urban, Rural, etc.).
- Color-coded by region: Australia, Canada, France, Germany, USA, etc.
- Helps companies understand where their strongest and weakest markets are in real time.

#### 6. **Regional Unit Performance**
- A visual showing units sold split by region (Central, East, West).
- Important for logistics and demand forecasting.

#### 7. **Revenue and Units by Year-Segment**
- A detailed breakdown of revenue and units based on customer segment (Convenience, Extreme, Moderate).
- Offers a fine-grained look into who’s buying and when.

---

### ⚙️ How It Works

- The dashboard connects to a **streaming dataset** hosted in Power BI Service.
- A **simulated data generator** (e.g., using Power Automate, Python, or push API) sends data to this stream at regular intervals.
- Each tile or chart auto-refreshes as new values enter the dataset.
- **No manual refresh** is needed — the dashboard remains live and constantly evolving.

---

### 🚀 Use Cases

- **Retail chains** monitoring hourly or daily performance.
- **Sales teams** tracking performance during product launches or campaigns.
- **Executives** needing a centralized view of real-time KPIs.
- **Call centers** watching inbound/outbound activity in real time.
- **Warehouse management** to monitor stock flow.

---

### 🛠️ Tools & Technologies

- **Microsoft Power BI Service**
- **Streaming Datasets / Push API**
- **Power Automate or Simulated API**
- **DAX & Power Query for data shaping**
- **Card, KPI, Line Chart, Bar Chart, and Time Series Visuals**

---

### 📌 Conclusion

This real-time dashboard project demonstrates how businesses can leverage **Power BI’s live streaming capability** to monitor and act on business-critical data as it happens. Whether you're tracking KPIs, sales, or customer demographics, a dashboard like this provides visibility, responsiveness, and agility — the essentials of modern business intelligence.

# OUTPUT
