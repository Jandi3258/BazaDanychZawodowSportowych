# 🏆 Sports Competition Management System
### (Baza Danych Zawodów Sportowych)

## 📌 Overview
This project is a comprehensive database management system designed to streamline the organization of sports competitions. It provides a robust structure for managing high-volume data related to athletes, technical staff, event logistics, and official results.

The system is built using **SQL Server**, ensuring data integrity and efficient relational mapping between participants, medical personnel, and event venues.

---

## 🚀 Features
* **Comprehensive Schema:** Dedicated tables for Athletes, Coaches, Referees, and Medical Staff.
* **Result Tracking:** Systematic recording of scores and final standings.
* **Staff Management:** Role-based management for coaching staff and safety personnel.
* **Infrastructure Logistics:** Tracking of sports facilities, stadiums, and event schedules.
* **Data Integrity:** Robust implementation of Primary and Foreign Key constraints to maintain relational consistency.

---

## 🛠 Tech Stack
* **Language:** SQL (T-SQL)
* **Platform:** Microsoft SQL Server
* **Tools:** SQL Server Management Studio (SSMS)

---

## 📂 Database Structure & ERD
The database architecture is divided into several logical modules:

* **Participants:** Detailed profiles of competitors including licensing and personal data.
* **Supervision:** Mapping of coaches to their respective athletes.
* **Logistics:** Comprehensive records of venues, stadiums, and competition timelines.
* **Health & Safety:** Assignments of medical staff to specific events.

### Entity Relationship Diagram (ERD)
![Database Diagram](Diagram.png) 
*> Note: Replace "Diagram.png" with the actual path to your image file in the repository.*

---

## 📖 How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Jandi3258/BazaDanychZawodowSportowych.git](https://github.com/Jandi3258/BazaDanychZawodowSportowych.git)
    ```

2.  **Setup:**
    * Open **SQL Server Management Studio (SSMS)**.
    * Connect to your instance.
    * Open and execute the `.sql` scripts to generate the database schema.
    * *(Optional)* Run the data insertion scripts to populate the tables with sample records.

3.  **Queries:**
    * Utilize the predefined scripts to generate reports such as winner lists, event schedules, or staff duty rosters.

---

## 📝 Author
Developed by [Jandi3258](https://github.com/Jandi3258).
