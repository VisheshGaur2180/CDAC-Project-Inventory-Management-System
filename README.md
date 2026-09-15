# Hardware Inventory Management System

A Python-based **Command-Line Inventory Management System** developed as part of the **CDAC – Mastering Programming Using Python** course.

The system helps manage hardware products, track inventory, maintain transaction records, generate reports, and visualize inventory data.

---

## 📌 Features

- Add, view, update, delete and search products
- Stock IN and Stock OUT management
- Automatic prevention of negative stock
- Transaction history
- Low-stock identification
- Date-wise stock summary
- Inventory value calculation
- Automatic Product ID renumbering after deletion
- Low-stock bar chart
- Category-wise inventory value pie chart
- Stock IN/OUT trend line chart
- Persistent data storage using JSON

---

## 🛠️ Technologies Used

- **Python** – Core programming language
- **JSON** – Data storage
- **Matplotlib** – Data visualization
- **CLI** – User interface
- **VS Code** – Development environment

---

## 📂 Project Structure

```text
Hardware-Inventory-Management-System/
│
├── main.py
├── product.py
├── stock.py
├── database.py
├── reports.py
├── seed_data.py
├── inventory.json
├── README.md
│
└── charts/
    ├── low_stock_chart.png
    ├── category_value_chart.png
    └── stock_trend_chart.png
