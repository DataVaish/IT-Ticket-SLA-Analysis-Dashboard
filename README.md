# IT Ticket & SLA Analysis Dashboard

## 🔍 Project Overview

Designed an end-to-end IT Ticket & SLA analysis dashboard using Power BI, SQL Server, and SSIS to monitor IT service performance and reduce SLA breaches through data insights. This project tracks ticket trends, SLA compliance, resolution performance, and support efficiency to improve decision-making for IT service teams.

---

## ✅ Key Features

* SLA breach analysis with root cause insights
* Ticket resolution performance by agent and priority
* Interactive drill-down by category, geography, and status
* Automated ETL pipeline using SSIS and SQL Server
* Centralized data model for scalable reporting

---

## 🛠️ Tech Stack

| Technology      | Used For                              |
| --------------- | ------------------------------------- |
| **Power BI**    | Data visualization & dashboard design |
| **SQL Server**  | Data storage & data cleaning          |
| **SSIS**        | ETL pipeline automation               |
| **Power Query** | Data transformation                   |
| **DAX**         | KPIs & business logic                 |
| **Excel**       | Source data preparation               |

---

## 📊 KPIs Included

* Total Tickets
* Pending Tickets
* Resolved Tickets
* SLA Met %
* Average Resolution Time
* Average Response Time
* Tickets by Agent
* Tickets by Priority (Critical/High/Medium/Low)
* Tickets by Category (Hardware, Software, Network, Cloud, etc.)
* Ticket Status Trend (Open, In Progress, Resolved, Closed)
* SLA Compliance Trend Over Time

---

## 🗂️ Dataset Information

This project uses real-world IT helpdesk data modeled in a **star schema**.

### 🧱 Data Model (Star Schema)

Fact Table:

* `FactTickets`

Dimension Tables:

* `DimAgent`
* `DimPriority`
* `DimCategory`
* `DimSLA`
* `DimStatus`
* `DimGeography`

---

## 📸 Dashboard Preview

<img width="1920" height="1080" alt="Screenshot 2025-10-29 222520" src="https://github.com/user-attachments/assets/f61d7d76-8a69-4665-9902-60ebf8de6ff3" />
<img width="1920" height="1080" alt="Screenshot 2025-10-29 222526" src="https://github.com/user-attachments/assets/6830b611-00fd-4b70-8c82-4e7bf1fae139" />
<img width="1920" height="1080" alt="Screenshot 2025-10-29 222532" src="https://github.com/user-attachments/assets/3ff8cff5-4a45-4de1-8f92-7abfeffb1d11" />
<img width="1920" height="1080" alt="Screenshot 2025-10-29 222541" src="https://github.com/user-attachments/assets/ccb1b843-20ee-4fa6-9bf1-d42d8b9f63fb" />
<img width="1920" height="1080" alt="Screenshot 2025-10-29 222552" src="https://github.com/user-attachments/assets/2bfbaa93-0fc1-4f34-b5b6-1667616723e5" />








