# civic-tech-learning
Notes, datasets, and small Python/SQL scripts for civic tech and public safety analytics.
# Public Safety & Federal Intelligence Analytics

A data analytics sandbox bridging criminal justice theory, civic tech, and computer science using Python and SQL. 

This project simulates real-world public safety operations—including emergency response SLA monitoring, cross-table federal case assignments, and geospatial threat analysis.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3
* **Libraries:** `pandas`, `sqlite3`
* **Query Language:** Relational SQL (`CREATE TABLE`, `LEFT JOIN`, conditional `CASE` aggregation)
* **Environment:** Google Colab & GitHub

---

## 📌 Project Key Features

### 1. SLA Delay Detection & Response Monitoring
* Calculated average emergency response times by incident category.
* Applied conditional logic (`lambda` functions) to flag calls exceeding a 10-minute Service Level Agreement (SLA) as **Delayed**.
* Isolated high-priority incidents for SLA compliance auditing.

### 2. Federal Intelligence & Cross-Table SQL Joins
* Created multi-table relational schema connecting `intelligence_logs` (cases) with `field_agents` (personnel).
* Executed SQL `LEFT JOIN` queries filtering high-threat cases assigned to federal agencies (**FBI**, **CIA**) along with security clearance levels (`Top Secret`, `Secret`).

### 3. Geospatial & District Threat Aggregation
* Structured spatial data including sector zones and GPS coordinates (Latitude/Longitude).
* Queried incident volume and high-threat concentrations grouped by city districts to assist in patrol/agent resource allocation.

---

## 🚀 How to Run
Open the main notebook directly in Google Colab:
* `public_safety_intel_analytics.ipynb`
