# Gamer's Stop — Video Game Store Management System

A console-based application for managing a video game store's inventory and customer purchases. Built with Python and Pandas, it stores login, stock, and purchase data in CSV files.

## Features

### Admin Panel
- Password-protected access
- Add and delete games or gaming devices
- Update item prices and quantities
- Display all stock
- Change the admin password

### Customer Panel
- View available items
- Purchase items
- Automatically update stock after a purchase
- Save purchase history

## Tech Stack

- Python
- Pandas
- Tabulate
- CSV files for persistent data storage

## How to Run

1. Install Python.
2. Install the required packages:

   ```bash
   pip install pandas tabulate
   ```

3. From the project directory, run the updated application:

   ```bash
   python Project_Updated
   ```

   Alternatively, open `Project.ipynb` in Jupyter Notebook and run its cells.

The initial admin credentials in `login.csv` are `Admin` / `Pass`. Change the password from the Admin Panel after logging in.

## File Structure

```text
.
├── Project_Updated   # Updated console application
├── Project.ipynb     # Jupyter Notebook version
├── login.csv         # Admin login credentials
├── stock.csv         # Inventory records
├── purchase.csv      # Purchase history
└── README.md
```
