
# Bookstore Inventory & Sales Analytics System

## Overview

This project is a Bookstore Management System developed in Python using an object-oriented approach. It manages bookstore inventory, records sales transactions, and performs data analysis with visualizations to generate business insights.

The system uses CSV files (`inventory.csv` and `sales.csv`) for data storage and integrates Pandas and NumPy for efficient data handling and analysis.

---

## Features

### Inventory Management
- Add new books with title, author, genre, price, and quantity
- Update stock by increasing or decreasing quantity
- Remove books from inventory

### Sales and Revenue Tracking
- Record book sales transactions
- Maintain sales data in CSV format

### Data Analysis
- Calculate total revenue using NumPy
- Identify top 5 best-selling books
- Analyze monthly revenue and sales growth
- Evaluate revenue distribution by genre

### Data Visualization
- Bar chart for books sold by genre
- Line chart for monthly sales trends and growth
- Pie chart for revenue distribution by genre
- Heatmap showing correlation between price and sales

---

## Tech Stack

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- datetime

---

## Requirements

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
````

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/krinasuthar19/Bookstore_System.git
```

2. Navigate to the project directory:

```bash
cd Bookstore_System
```

3. Run the main script:

```bash
python main.py
```

4. Follow the menu options to manage inventory and analyze sales data

---

## Data Files

### inventory.csv

Contains information about books:

* Book ID
* Title
* Author
* Genre
* Price
* Quantity

### sales.csv

Contains sales transaction details:

* Sale ID
* Book ID
* Quantity Sold
* Total Price
* Date

---

## Use Cases

* Bookstore inventory management
* Sales tracking and reporting
* Business data analysis and visualization
* Academic and portfolio project

---

## Limitations

* Data is stored in CSV files (not suitable for large-scale systems)
* CLI-based interface (no GUI)
* Requires correct input format from the user

---

## Future Improvements

* Add graphical interface using Tkinter or Streamlit
* Integrate database (MySQL or SQLite)
* Add user authentication system
* Improve error handling and validation

---

## Conclusion

This project demonstrates the practical application of Python, Pandas, and NumPy for building a real-world data-driven system. It combines inventory management with analytics and visualization, making it suitable for learning and portfolio demonstration.

