# Data Engineering Technical Challenge: Retail Data Modeling

## 1. About This Exercise
This technical exercise is intended to assess your ability to **create a dimensional data model** and perform **basic data transformation** to populate that model.

* **Timeline:** The task is expected to take up to **2 hours** to complete.
* **Submission:** You are not required to submit your solution in advance. However, you must be prepared to share your screen and walk through your solution during the second interview.

---

## 2. Task Background
You are a Data Engineer at a retailer that sells electrical appliances. [cite: 7, 28] The retailer uses an operational system to track sales.While core entity data is stored in relational tables, transaction data is now being exported as semi-structured objects.

You have been asked to:
1. **Design a dimensional data model** (Star Schema) to form the basis of a new data warehouse.
2. **Build an ETL process** in Python to transform the mixed-format operational data into the structures required for your new model.

### Operational Schema & Data Formats
The operational system team has provided a combination of flat files and a nested transaction export:

* **Relational Extracts (CSV):** `customers.csv`, `products.csv`, `categories.csv`, and `delivery_methods.csv` contain the core business dimensions.
* **Transaction Export (JSON):** `orders.json` contains the order headers with **nested arrays** of order items and system metadata.

Your challenge is to successfully **flatten and join** these disparate formats into a clean, unified dimensional model that follows the **Kimball methodology**.

---

## 3. Source Data
The operational system team has provided sample extracts to enable you to build your transformation process. These can be found in the:
`source_data/` directory.

---

## 4. The Task

### Part 1: Dimensional Modeling
Create a dimensional model (Star or Snowflake schema) to store the data from the operational system. 
* **Deliverable:** A diagram of your proposed model.

### Part 2: Data Transformation
Create a process in **Python** that transforms the source data into your dimensional model.
* **Deliverable:** The output should be either a populated database (e.g., SQLite) or a set of CSV files, with each file representing a table from your new model.

### Part 3: Interview Presentation
During the interview, you will:
* Talk the interviewers through your **data model** and **Python code**.
* Explain the **decisions and assumptions** you made during the process.
* **Execute the code** to demonstrate that it works successfully.

---

## 5. Technical Notes
* **Libraries:** You are free to use any Python libraries or frameworks (e.g., Pandas, PySpark, SQLAlchemy, etc.).
* **Testing:** Automated testing is not mandatory for this exercise, but be prepared to explain your **testing strategy** and how you would ensure data quality in a production environment.





# Reach Data Platform: Technical Challenge

## 1. About This Exercise
[cite_start]This technical exercise is intended to assess your ability to **create a dimensional data model** and perform **basic data transformation** to populate that model. [cite: 3, 24]

* [cite_start]**Timeline:** The task is expected to take up to **2 hours** to complete. [cite: 5, 26]
* **Submission:** You are not required to submit your solution in advance. [cite_start]However, you must be prepared to **share your screen** and walk through your solution during the second interview. [cite: 4, 25]

---


---

## 3. Source Data
The operational system team has provided sample extracts to enable you to build your transformation process. These can be found in the:
[cite_start]`source_data/` directory. [cite: 12, 33]

---

## 4. The Task

### Part 1: Dimensional Modeling
[cite_start]Create a dimensional model to store the data from the operational system. [cite: 14, 35]
* [cite_start]**Deliverable:** A diagram of your proposed model. [cite: 14, 35]

### Part 2: Data Transformation
[cite_start]Create a process in **Python** that transforms the source data into your dimensional model. [cite: 15, 36]
* [cite_start]**Deliverable:** The output can be either a populated database (e.g., SQLite) or a set of CSV files, with each file representing a table from your new model. [cite: 16, 37]

### Part 3: Interview Presentation
At your second interview, you will:
* [cite_start]Talk the interviewers through your **data model**, **Python code**, and the **decisions and assumptions** you made. [cite: 17, 38]
* [cite_start]**Execute the model** to demonstrate that it works successfully. [cite: 18, 39]

---

## 5. Technical Notes
* [cite_start]**Libraries:** You are free to use any Python libraries or frameworks you wish (e.g., Pandas, PySpark, SQLAlchemy). [cite: 20, 41]
* [cite_start]**Testing:** Automated testing is not required, but be prepared to explain your **testing strategy** and how you would ensure data quality in a production environment. [cite: 21, 42]