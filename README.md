# 🎮 Gamer's Stop

### Video Game Store Management System

Gamer's Stop is a Python-based, console application for managing a video game store. Admins can maintain the inventory, while customers can browse and purchase available games and gaming devices. Store data is saved locally in CSV files.

## ✨ Features

### 🛠️ Admin Panel
- 🔐 Password-protected access
- ➕ Add games and gaming devices
- 🗑️ Delete items
- 💲 Update item prices
- 📦 Update stock quantities
- 📋 Display all inventory
- 🔑 Change the admin password

### 🛍️ Customer Panel
- 👀 View available items
- 🧾 Purchase items
- 📉 Automatically reduce stock after a purchase
- 🗂️ Save purchase history

## 🧰 Technology

| Technology | Purpose |
|---|---|
| Python | Application logic |
| Pandas | Data handling |
| Tabulate | Formatted console tables |
| CSV | Persistent local data storage |

## 🚀 Getting Started

### Requirements

- Python 3
- `pandas`
- `tabulate`

### Installation and Run

1. Clone the repository and open its directory.
2. Install the required packages:

   ```bash
   pip install pandas tabulate
   ```

3. Start the application:

   ```bash
   python Project_Updated
   ```

   You can also open `Project.ipynb` in Jupyter Notebook and run the notebook cells.

The initial admin login is `Admin` / `Pass`. For security, change the password in the Admin Panel after your first login.

## 🗃️ Project Files

```text
.
├── Project_Updated   # Console application
├── Project.ipynb     # Jupyter Notebook version
├── login.csv         # Admin login credentials
├── stock.csv         # Inventory data
├── purchase.csv      # Purchase history
└── README.md         # Project documentation
```
