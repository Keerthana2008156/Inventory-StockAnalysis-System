# StockWise – Inventory and Stock Analysis System

## Project Overview
StockWise is a web-based Inventory and Stock Analysis System developed using Python, Flask, MySQL, HTML, and CSS. It helps businesses manage products, monitor stock levels, record stock transactions, and analyze inventory movement efficiently.

## Features
- Dashboard with inventory summary
- Add and manage products
- Edit product details
- Manage product categories and suppliers
- Record Stock IN and Stock OUT transactions
- Track stock adjustments
- Low-stock alerts
- Current stock calculation
- Inventory valuation
- Fast-moving and slow-moving product analysis
- Stock movement graphs and reports
- Stock audit logging

## Technologies Used
- **Frontend:** HTML, CSS
- **Backend:** Python, Flask
- **Database:** MySQL
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib

## Database Tables
1. categories
2. suppliers
3. products
4. stock_transactions
5. stock_adjustments
6. stock_audit_log

## Project Structure
```text
StockWise-Inventory-System/
│
├── app.py
├── database.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   ├── add_product.html
│   ├── edit_product.html
│   ├── adjustments.html
│   ├── analysis.html
│   └── transactions.html
│
└── static/
    └── style.css
```

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Keerthana2008156/StockWise-Inventory-System.git
```

### 2. Navigate to the Project Folder
```bash
cd StockWise-Inventory-System
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure MySQL
- Create the database `stock_analysis_db`.
- Configure your MySQL connection details securely.
- Create the required database tables.

### 5. Run the Application
```bash
py app.py
```

Open your browser and visit:
`http://127.0.0.1:5000/`

## Project Objective
The main objective of StockWise is to simplify inventory management, improve stock monitoring, reduce manual errors, and provide useful insights into inventory movement and product performance.

## Future Enhancements
- Online cloud deployment
- User authentication and role management
- Advanced inventory analytics
- Automated stock notifications

## Author
**StockWise – Inventory and Stock Analysis System**

Developed as an academic project.
