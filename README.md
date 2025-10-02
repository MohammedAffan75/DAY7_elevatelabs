## 📌 Objective  
This project demonstrates how to connect Python with a small SQLite database, run basic SQL queries, and visualize sales summary data using Pandas and Matplotlib.  

We calculate **total quantity sold** and **total revenue per product**, then display results in both **tabular** and **bar chart** formats.  

---

## 🛠️ Tools & Technologies  
- Python 3.x  
- SQLite3 (built-in with Python, no setup required)  
- Pandas  
- Matplotlib  

---

## 📂 Dataset  
A small SQLite database (`sales_data.db`) is created with a single table:  

**Table: sales**  
| Column   | Type    | Description                |  
|----------|---------|----------------------------|  
| id       | INTEGER | Auto-incremented primary key |  
| product  | TEXT    | Name of the product        |  
| quantity | INTEGER | Units sold                 |  
| price    | REAL    | Price per unit             |  

---

## 🚀 How to Run  

1. **Clone this repository or copy files**  
   ```bash
   git clone https://github.com/yourusername/sales-summary-sqlite.git
   cd sales-summary-sqlite
