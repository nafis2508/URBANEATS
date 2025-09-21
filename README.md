Alright 🚀 here’s a polished **README.md** for your GitHub repo. I’ve written it in a professional portfolio style with embedded image placeholders (you can adjust the filenames to match your screenshot uploads).

---

# 🍴 UrbanEats Business Analytics Project

## 📌 Overview

UrbanEats is a case study designed to demonstrate the integration of **database design, data population, and SQL-based business analytics** for a multi-branch café chain.

The project covers:

* **Database schema design** with relational integrity.
* **Dummy data population** across outlets, customers, products, orders, payments, reservations, and staff.
* **SQL-driven business analysis** focused on five core business concerns.
* **Insights and strategic recommendations** for improving sales, customer retention, menu optimisation, staff scheduling, and operational efficiency.

---

## 📂 Repository Structure

```
├── tables.sql                # Database schema creation  
├── Dat_Insertion.sql         # Dummy data population  
├── BusinessCaseAnalysis.sql  # Business concern SQL queries  
├── UrbanEats_Report.pdf      # Full report with insights  
├── ERD.png                   # Entity Relationship Diagram  
└── Screenshots/              # Query result outputs (for each concern)  
```

---

## 🛠️ Database Schema & ERD

The UrbanEats schema models core business entities:

* **Outlet** – café branches.
* **Customer** – customer profiles and reservations.
* **Product & Product\_Category** – menu items and categories.
* **Orders & Payments** – transactions and revenue.
* **Staff & Shifts** – workforce management.
* **Junction tables** – `Order_Product`, `Outlet_Product`, `Staff_Shift` for many-to-many relationships.

**Entity Relationship Diagram (ERD):**

![ERD](ERD.png) 
An interactive version of the ERD is available on [Miro](https://miro.com/app/board/uXjVJG44XM0=/?share_link_id=596986380337) for deeper exploration.


---

## 🧑‍💻 Dummy Data

The dataset contains **3 outlets, 30+ staff members, 30+ customers, and 30+ menu items**. It simulates real-world operations, including:

* **Repeat vs one-time customers**
* **No-shows and cancellations** in reservations
* **Product availability differences** across outlets
* **Staff allocation by shifts**

---

## 📊 Business Concerns & Insights

### 1️⃣ Sales & Profitability

**Focus:** Revenue streams by outlet and product category.
**Key Insight:** Central is the most profitable outlet with balanced revenue across meals, beverages, and desserts. Harbour thrives on niche cold drinks and desserts, while Campus faces profitability issues due to cancellations and limited menu options.

![Sales & Profitability Screenshot](Screenshots/business_concern_1.png)

---

### 2️⃣ Customer Retention

**Focus:** Loyalty segmentation, no-shows, and failed payments.
**Key Insight:** Loyalty is fragile and often category-specific. Failed/refunded payments strongly overlap with no-shows, creating churn risk. Harbour converts reservations into orders best, while Campus suffers severe reliability issues.

![Customer Retention Screenshot](Screenshots/business_concern_2.png)

---

### 3️⃣ Menu Optimisation

**Focus:** Identifying low-performing products and categories.
**Key Insight:** Menu contains underperforming items (e.g., Espresso Classics, Caesar Salad). Central balances meals and beverages effectively, Harbour thrives on desserts and drinks, while Campus lacks meal diversity.

![Menu Optimisation Screenshot](Screenshots/business_concern_3.png)

---

### 4️⃣ Staff Scheduling & Performance

**Focus:** Shift utilisation and staffing balance.
**Key Insight:** Central maintains strong role coverage but risks overstaffing in some shifts. Harbour requires more baristas than chefs due to its drinks-heavy demand. Campus suffers from unstaffed shifts, reducing service reliability.

![Staff Scheduling Screenshot](Screenshots/business_concern_4.png)

---

### 5️⃣ Branch-Level Operational Efficiency

**Focus:** Menu breadth, reservation reliability, and revenue per branch.
**Key Insight:** Central is the benchmark outlet with maximum menu breadth and high reservation reliability. Harbour performs well in its niche but needs better stock consistency. Campus is a major bottleneck due to poor execution rather than lack of demand.

![Branch Efficiency Screenshot](Screenshots/business_concern_5.png)

---

## ⚙️ How to Run

1. Clone this repository.
2. Create a new MySQL database.
3. Run `tables.sql` to create the schema.
4. Run `Dat_Insertion.sql` to populate dummy data.
5. Run `BusinessCaseAnalysis.sql` to execute business concern queries.
6. View outputs in **MySQL Workbench** or your preferred SQL IDE.


## 📑 Conclusion

UrbanEats analysis highlights three distinct outlet profiles:

* **Central** – most profitable and balanced, serving as the operational benchmark.
* **Harbour** – strong tourist-driven niche with cold drinks and desserts.
* **Campus** – underperforming branch with menu, staffing, and reservation challenges.

The database and queries together provide actionable insights to optimise menu design, strengthen customer retention, improve staffing efficiency, and align operational benchmarks across branches.

---

## 🚀 Future Improvements

* **BI Integration** → Build interactive dashboards in Power BI/Tableau.
* **Predictive Analytics** → Forecast demand and predict customer churn.
* **Scalability** → Expand with seasonal variations and additional outlets.
* **Automation** → Use triggers/stored procedures for automated reporting.
* **Cloud Deployment** → Host the database on AWS RDS or Azure SQL for scalability.

---

✨ *This project combines technical SQL development with business-focused insights, making it both a database design showcase and a practical analytics case study.*

