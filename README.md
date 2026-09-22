# 📱 PhonePe Transaction Analytics Dashboard

## 📊 Power BI Project

An interactive **PhonePe Transaction Analytics Dashboard** built using **Microsoft Power BI** to analyze transaction performance, transaction value, user behavior, services, payment status, age segments, and monthly trends.

The dashboard provides a consolidated view of key business KPIs and allows users to explore transaction patterns through interactive filters and visualizations.

---

## 🖼️ Dashboard Overview

The dashboard focuses on:

* 💰 Total Transaction Value
* 🔢 Total Transactions
* 👥 Total Users
* ✅ Transaction Success Rate
* 📈 Monthly Transaction Trends
* 💳 Payment Status Analysis
* 📱 Service-wise Transaction Analysis
* 👤 User Age Segment Analysis
* 📅 Weekend vs Weekday Transactions
* 🏆 User-wise Transaction Value
* 📊 Month-wise Performance

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze overall PhonePe transaction performance.
2. Track total transaction value and transaction volume.
3. Understand monthly transaction trends.
4. Analyze transactions across different services.
5. Identify transaction behavior across age segments.
6. Compare weekend and non-weekend transaction activity.
7. Analyze payment status and transaction success.
8. Identify users contributing higher transaction values.
9. Build an interactive and easy-to-understand business dashboard.

---

## 📌 Key KPIs

The dashboard contains the following major KPIs:

| KPI                          | Description                           |
| ---------------------------- | ------------------------------------- |
| 💰 Total Transaction Value   | Total monetary value of transactions  |
| 🔢 Total Transactions        | Number of transactions                |
| 👥 Total Users               | Number of users in the dataset        |
| ✅ Success Rate               | Percentage of successful transactions |
| 📈 Monthly Transaction Value | Transaction value by month            |
| 📊 Monthly Transaction %     | Monthly contribution/variation        |
| 🔄 Transaction Value %       | Transaction value percentage analysis |

---

## 📊 Dashboard Visualizations

### 1. Total Transaction Value

A KPI card showing the overall transaction value generated across the dataset.

### 2. Total Transactions

Displays the total number of transactions.

### 3. Total Users

Shows the total number of users available in the dataset.

### 4. Success Rate

Shows the percentage of successful transactions.

### 5. Monthly Transaction Trend

A line chart is used to analyze:

* Month
* Total Transaction Value
* Total Transactions

This helps identify changes in transaction activity over time.

### 6. Service-wise Transactions

A column chart analyzes transaction volume across different PhonePe services.

### 7. Age Segment Analysis

A donut chart categorizes users into different age segments and displays the corresponding user distribution.

### 8. Weekend Analysis

A donut chart compares transaction activity between:

* Weekend
* Non-Weekend

### 9. User-wise Transaction Value

A column chart analyzes transaction value by individual users.

### 10. Payment Status Filter

An interactive slicer allows users to filter the dashboard according to payment status.

### 11. Month Filter

An interactive month slicer allows users to analyze specific months.

---

## 🗂️ Dashboard Structure

The Power BI report contains:

```text
PhonePe Dashboard
│
├── KPI Cards
│   ├── Total Transaction Value
│   ├── Total Transactions
│   ├── Total Users
│   └── Success Rate
│
├── Time Analysis
│   ├── Monthly Transaction Trend
│   ├── Monthly Transaction Value
│   └── Monthly Transaction %
│
├── Transaction Analysis
│   ├── Service-wise Transactions
│   ├── Payment Status
│   └── Weekend Analysis
│
├── Customer Analysis
│   ├── Age Segment
│   └── User-wise Transaction Value
│
└── Interactive Filters
    ├── Month
    └── Payment Status
```

---

## 🧮 Data Model

The report uses separate logical tables for transaction, user, date, and measures.

### Main Tables

```text
All_Transactions
│
├── Transaction information
├── Service
├── Service Type
└── Payment Status

All_Users
│
├── User ID
├── Name
├── Age
└── Age Segment

Date_Table
│
├── Month
└── Weekend

Measure
│
├── Total Transaction
├── Total Transaction Value
├── Transaction Value %
├── Total Transaction %
└── Success Rate
```

---

## 🛠️ Tools & Technologies

| Technology             | Purpose                             |
| ---------------------- | ----------------------------------- |
| **Microsoft Power BI** | Dashboard development               |
| **Power Query**        | Data preparation and transformation |
| **DAX**                | Measures and KPI calculations       |
| **Data Modeling**      | Relationships and analytical model  |
| **Power BI Visuals**   | Interactive visualization           |

---

## 📐 DAX Measures

The project uses measures for important business metrics such as:

```DAX
Total Transaction
```

```DAX
Total Transaction Value
```

```DAX
Success Rate
```

```DAX
Total Users
```

```DAX
Total Transaction %
```

```DAX
Trans Value Mon%
```

```DAX
Total Trans Mon%
```

These measures are used throughout the dashboard to create dynamic KPIs and visualizations.

---

## 🔍 Business Questions Answered

This dashboard can help answer questions such as:

* What is the total transaction value?
* How many transactions were completed?
* How many users are using the platform?
* What is the transaction success rate?
* Which months have higher transaction activity?
* Which services generate more transactions?
* How does transaction activity differ by age segment?
* How much transaction activity occurs on weekends?
* What is the transaction distribution by payment status?
* Which users have higher transaction values?
* How does transaction value change month by month?

---

## 📈 Key Insights

The dashboard can be used to identify:

* Transaction growth or decline over time.
* High-performing services.
* User demographic patterns.
* Weekend transaction behavior.
* Payment-status distribution.
* High-value users.
* Monthly transaction contribution.
* Overall transaction performance.

> **Note:** Specific business conclusions should be interpreted from the current dashboard filters and underlying dataset.

---

## 🎨 Dashboard Features

### Interactive Filters

Users can dynamically filter the dashboard using:

* 📅 Month
* 💳 Payment Status

### Interactive Visual Analysis

Selecting a data point in one visualization can interact with other visuals, making it easier to drill into specific transaction patterns.

### Tooltip Analysis

Additional visualizations are available through tooltip pages for:

* Service Type transaction analysis
* Service Type transaction value analysis

---

## 📁 Project Files

Recommended GitHub repository structure:

```text
PhonePe-PowerBI-Analytics/
│
├── README.md
│
├── PowerBI/
│   └── phone_pe.pbix
│
├── Dataset/
│   └── phonepe_transactions.csv
│
├── Screenshots/
│   └── dashboard.png
│
└── Documentation/
    └── project-notes.md
```

---

## 🚀 How to Use

### Step 1 — Download the Repository

Clone the repository:

```bash
git clone https://github.com/your-username/PhonePe-PowerBI-Analytics.git
```

### Step 2 — Open Power BI

Open **Microsoft Power BI Desktop**.

### Step 3 — Open the Report

Open:

```text
PowerBI/phone_pe.pbix
```

### Step 4 — Interact With the Dashboard

Use the available filters and visuals to explore:

```text
Month
Payment Status
Service
Age Segment
Weekend
```

---

## 💡 Skills Demonstrated

This project demonstrates practical skills in:

* Power BI
* Data Visualization
* Dashboard Development
* Data Modeling
* DAX
* Power Query
* KPI Development
* Business Analytics
* Time-Series Analysis
* Customer/User Analysis
* Transaction Analysis
* Interactive Reporting

---

## 📸 Dashboard Preview

Add your dashboard screenshot here:

```markdown
![PhonePe Dashboard](Screenshots/dashboard.png)
```

---

## 🔮 Future Improvements

Potential improvements include:

* Add Year and Quarter filters.
* Add Region/State-level analysis.
* Add transaction growth KPIs.
* Add YoY and MoM analysis.
* Add geographical visualization.
* Add forecasting.
* Add anomaly detection.
* Add customer segmentation.
* Add drill-through pages.
* Add mobile-optimized dashboard layout.
* Add automated data refresh.

---

## 👨‍💻 Author

Akshay Mevada

Data Analytics | Power BI | SQL | Python | Excel

---

## ⭐ If You Find This Project Useful

If this project helps you learn Power BI or data analytics, consider giving the repository a ⭐.

---

## 📄 License

This project is intended for **educational and portfolio purposes**.

The PhonePe name and related trademarks belong to their respective owners.
