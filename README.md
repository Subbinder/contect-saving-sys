

# Contact Management System

A simple Python-based application created in a **Jupyter Notebook** to manage contact records. It uses **Tkinter** for the interface and **SQLite** for the database.

## 📋 Features
* **Add Contacts**: Save member details like name, age, gender, and address.
* **Display Table**: View all saved records in a structured list.
* **Update & Delete**: Easily modify existing information or remove records.
* **Data Storage**: Saves all information to a local file named `contact.db`.

## 🚀 How to Use
1. Open the `contect_men.ipynb` file in **Jupyter Notebook**.
2. Run the main code cell.
3. Use the **+ ADD NEW** button to start entering contacts.
4. **Double-click** any row in the table to update that contact's information.

## ⚠️ Note on Errors
* Ensure the **Age** field only contains numbers. Entering text in the Age field will cause a `ValueError`.

## 🛠️ Requirements
* Python 3.x
* Jupyter Notebook
* Tkinter (standard Python library)
