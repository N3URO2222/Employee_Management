# Employee Management System

A simple **menu-driven Python program** to manage employee records using dictionaries.  
This project demonstrates basic data storage, retrieval, and search operations in Python.

---

## 📌 Features
- **Add Employee**: Add new employee details with validation for unique Employee ID.
- **View All Employees**: Display all employees in a table-like format.
- **Search Employee**: Search for an employee by their ID.
- **Exit**: Quit the program with a thank-you message.

---

## 🛠️ Project Structure
The project is organized into functions for clarity and modularity:

- `main_menu()`: Displays the main menu and handles user choices.
- `add_employee()`: Adds a new employee to the dictionary.
- `view_employees()`: Displays all employee details.
- `search_employee()`: Searches for an employee by ID.

---

## 📂 Sample Data
The program starts with some sample employees for testing:

```python
employees = {
    101: {'name': 'Satya', 'age': 27, 'department
