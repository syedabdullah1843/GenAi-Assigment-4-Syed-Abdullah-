# Python File Handling – Assignment 4

This repository contains my **Python File Handling Assignment**, covering basic file operations such as creating, writing, reading, appending, updating, and safely accessing files.

## 📌 Assignment Overview

The assignment demonstrates how Python can be used to work with text files using built-in file-handling functions and methods.

### Concepts Covered

* Creating and writing files
* Reading files using different methods
* Appending data to existing files
* Processing data stored in files
* Generating summary reports
* Taking user input and storing it in files
* Checking whether a file exists
* Calculating discounted prices
* Generating formatted reports

---

## 📂 Project Structure

```text
GenAI-Task4/
│
├── task1_write_sales.py
├── task2_read_sales.py
├── task3_append_sales.py
├── task4_summary_report.py
├── task5_product_info.py
├── task6_safe_file_read.py
├── task7_discounted_prices.py
│
├── sales_data.txt
├── Products.txt
├── discount_report.txt
│
└── README.md
```

---

## 📝 Task 1 – Write Sales Records

**File:** `task1_write_sales.py`

This task creates a list of sales values and writes each value into `sales_data.txt`.

### Operations performed

* Creates a sales list.
* Opens the file in write mode using `"w"`.
* Writes each sales value on a separate line.
* Reads the file again and displays the stored data.

Example sales data:

```text
1200
450
980
1500
3000
```

---

## 📖 Task 2 – Read File in Different Ways

**File:** `task2_read_sales.py`

This task demonstrates three different ways of reading a file.

### Methods used

1. `read()` – Reads the complete file.
2. `readline()` – Reads one line at a time.
3. `readlines()` – Reads all lines and stores them in a list.

The sales values are also converted from strings into integers for further processing.

---

## ➕ Task 3 – Append New Sales

**File:** `task3_append_sales.py`

This task adds new sales records to the existing `sales_data.txt` file without deleting the existing data.

### Operations performed

* Opens the file using append mode `"a"`.
* Adds new sales values.
* Reads the updated file.
* Counts the total number of lines.

New sales added:

```text
5000
2500
1700
```

---

## 📊 Task 4 – Generate Sales Summary

**File:** `task4_summary_report.py`

This task reads the sales data from `sales_data.txt` and generates a summary.

### Calculations performed

* Total Sales
* Highest Sale
* Lowest Sale
* Average Sale

The program uses Python's built-in functions:

```python
sum()
max()
min()
len()
```

Example output:

```text
Sales Summary Report
--------------------
Total Sales: 15330
Highest Sale: 5000
Lowest Sale: 450
Average Sale: 1916.25
```

---

## 🛍️ Task 5 – Create Product Information File

**File:** `task5_product_info.py`

This task collects product information from the user and stores it in `Products.txt`.

The program asks the user to enter:

* Product name
* Product price

The information is then written in the following format:

```text
Product Name | Price
```

Example:

```text
Laptop | 55000.00
Mouse | 500.00
Keyboard | 800.00
```

---

## 🛡️ Task 6 – Safe File Reading

**File:** `task6_safe_file_read.py`

This task demonstrates how to safely check whether a file exists before attempting to read it.

The program uses:

```python
os.path.exists()
```

If the file exists, its contents are displayed.

If the file does not exist, the program displays:

```text
File not found. Please check the filename.
```

This prevents errors caused by trying to open a file that does not exist.

---

## 💰 Task 7 – Discounted Price Report

**File:** `task7_discounted_prices.py`

This is the mini-project for the assignment.

The program contains product prices and asks the user to enter a discount percentage.

It calculates the discounted price for each product using:

```text
Discount Amount = Original Price × Discount Percentage / 100

Discounted Price = Original Price − Discount Amount
```

The results are stored in:

```text
discount_report.txt
```

The report contains:

```text
Product | Original Price | Discounted Price
```

It also calculates:

* Total number of products
* Average discounted price

---

## 🧰 Technologies Used

* **Python 3**
* Python File Handling
* Built-in Python functions
* `os` module

No external libraries are required.

---

## ▶️ How to Run

Make sure Python 3 is installed on your system.

Open the terminal inside the project folder and run:

```bash
python task1_write_sales.py
```

Then:

```bash
python task2_read_sales.py
python task3_append_sales.py
python task4_summary_report.py
python task5_product_info.py
python task6_safe_file_read.py
python task7_discounted_prices.py
```

For Tasks 5, 6, and 7, the program will ask for user input.

---

## ⚠️ Important

For the sales-data demonstration, run **Task 1 before Task 2, Task 3, and Task 4**.

Task 3 uses append mode, so running it multiple times will add the same sales values again.

---

## 🎯 Learning Outcomes

Through this assignment, I learned how to:

* Create and manage text files using Python.
* Write data into files.
* Read files using different methods.
* Append information without overwriting existing data.
* Process data stored in text files.
* Perform calculations using file data.
* Handle user input.
* Check file existence before reading.
* Generate simple formatted reports.

---

## 👨‍💻 Author

**Syed Abdullah**

Python / Data Science Learner

---

## 📄 License

This project is created for **educational and learning purposes**.
