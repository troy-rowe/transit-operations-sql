# Transit Operations SQL Project

This project models a fictional public transit agency and showcases strong SQL skills including database design, relational modeling, JOINs, aggregation, data analysis, and clean schema organization.  
It is designed as a complete portfolio project for demonstrating SQL proficiency.

---

## 🌐 Project Overview

This database simulates the core operations of a regional transit system, including:

- Bus routes  
- Stops within the transit network  
- Drivers  
- Vehicles  
- Daily scheduled trips  
- Ticketing, ridership, and revenue analytics  

The project is structured to reflect real-world database design patterns used by transportation agencies, logistics systems, and operations management software.

---

## 🧱 Database Schema

The database includes **six related tables**, each created in `schema.sql`:

- **routes** — route numbers, route names, and active/inactive status  
- **stops** — stop information and fare zones  
- **drivers** — driver names, hire dates, and employment status  
- **vehicles** — fleet information including type, capacity, and service status  
- **trips** — scheduled transit trips with relationships to routes, drivers, and vehicles  
- **tickets** — individual passenger tickets tied to trips and stops  

All relationships are handled using foreign keys to model real operational data.

---

## 📁 Project Structure

transit-operations-sql/
│
├── README.md ← Project overview (this file)
├── schema.sql ← All CREATE TABLE statements
├── seed_data.sql ← Your manually-written INSERT statements
│
├── queries/
│ ├── 01_basic_selects.sql
│ ├── 02_joins.sql
│ ├── 03_aggregates_and_grouping.sql
│ └── 04_case_and_formatting.sql
│
└── bonus/
├── cleanup_and_constraints.sql
└── views.sql


## ▶️ How to Use This Project

1. Create a new database in your SQL environment (e.g., SQLite, DataGrip, DBeaver, VS Code extension).  
2. Run **`schema.sql`** to create the database structure.  
3. Run **`seed_data.sql`** to insert all sample data.  
4. Execute queries inside the **`queries/`** folder:
   - Basic SELECTs  
   - JOINs  
   - Aggregations  
   - CASE and formatting operations  
5. Optional: explore advanced features inside the **`bonus/`** folder.

---

## 🎯 Learning Goals

This project demonstrates:

- Normalized table design  
- Realistic relationships via foreign keys  
- Clean DDL structure  
- Data seeding  
- Complex JOINs  
- Aggregate analytics  
- Query organization  
- SQL documentation and readability  

Perfect for a Computer Science, Data, or IT portfolio.

---

## 📘 Future Enhancements

Planned improvements include:

- Additional views for reporting  
- Index optimization  
- CHECK constraints for data validation  
- Weekday/weekend/holiday scheduling  
- Passenger categories (student, senior, disabled)  

---

## 👤 Author

**Troy Rowe**  
SQL | Python | Computer Science Student  
GitHub: https://github.com/wtrowe  
LinkedIn: https://www.linkedin.com/in/troy-rowe1  
