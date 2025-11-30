# SQL-JOMATO-ASSIGNMENT-3
This repository contains solutions for **SQL Mandatory Assignment 3** based on the Zomato dataset.   The tasks demonstrate practical SQL concepts including stored procedures, transactions, rollback, row numbering, loops, views, and triggers.  
## 📂 Tasks Covered

### 1. Stored Procedure
- Display restaurant name, type, and cuisine where table booking is not zero.
- Implemented using `CREATE PROCEDURE` and `CALL`.

### 2. Transaction & Rollback
- Update cuisine type `'Cafe'` to `'Cafeteria'`.
- Verified changes and rolled back to restore original data.

### 3. Row Number & Top 5 Areas
- Generated row numbers using `ROW_NUMBER()` window function.
- Extracted top 5 areas with highest restaurant ratings.

### 4. While Loop
- Printed numbers from 1 to 50 using a stored procedure with `WHILE`.

### 5. View
- Created a view `TopRatingRestaurants` to store top 5 highest rating restaurants.

### 6. Trigger
- Added a trigger `AfterInsertJomato` to display a message whenever a new record is inserted.

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sql-assignment-3.git
