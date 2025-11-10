# **File Analysis and SQL Query Practice — Python - Streamlit Demo App**

[![Live App](https://img.shields.io/badge/LIVE%20APP-CLICK%20TO%20VIEW-green?style=for-the-badge)](https://file-analysis-sql-demo-gv4tpcljrnpkmmr8kvo6ui.streamlit.app/)

This project is a **personal learning initiative** aimed at enhancing my skills in **Python** and **SQL** by building an interactive Streamlit application that simulates a real-world data analysis environment. 

It allows users to upload datasets, run SQL queries, and explore data dynamically, making it a perfect platform for practicing SQL operations and Python-based data handling.

---

##  **Why This Project?**

As part of my journey to strengthen my expertise in **data analysis** and **SQL querying**, I developed this application to:

-  **Practice SQL on Real Datasets:** Work with multiple file formats and execute SQL queries dynamically.  
-  **Explore Python Libraries:** Use `pandas`, `sqlite3`, and other powerful libraries to manipulate and analyze data.  
-  **Simulate Scenarios:** Create an environment where users can apply SQL commands to analyze simple datasets.  

---

##  **Key Features**

The app showcases the following core functionalities:

-  **Data Analysis** – Using `pandas` for efficient data manipulation.  
-  **SQL Query Execution** – Leveraging `SQLite` for in-memory SQL query processing.  
-  **Dataset Visualization** – Displaying query results dynamically with interactive tables.  
-  **Result Exporting** – Allowing users to download query results in `CSV` format.  
-  **File Handling** – Supporting multiple formats such as `CSV`, `Excel`, `Parquet`, and `JSON`.

---

##  **What This App Does**

###  **1. Upload or Select Files**
- Upload a dataset (`CSV`, `Excel`, `Parquet`, or `JSON`) or choose a predefined file from the repository.
- The application automatically detects column names and data types.

###  **2. SQL Query Execution**
- Write and execute SQL queries directly on the loaded dataset.
- Perform basic operations such as:
    ```sql
    SELECT * FROM data LIMIT 10;
    ```
    ```sql
    SELECT title, release_year FROM data WHERE type = 'Movie';
    ```

###  **3. View and Export Results**
- Visualize query results dynamically.
- Export results as a `CSV` file for further analysis.

---

##  **Technologies Used**

This project leverages several powerful Python libraries:

| Library    | Purpose                                           |
|------------|---------------------------------------------------|
| **Streamlit**  | Provides an intuitive and interactive web interface. |
| **Pandas**     | Handles data manipulation and analysis.          |
| **SQLite3**    | Enables SQL queries on the loaded dataset.        |
| **OpenPyXL**   | Processes Excel files (`.xlsx`).                  |
| **PyArrow**    | Reads and processes Parquet files.                |

---

##  **Technical Highlights**

⚡️ **Streamlit:** Builds a modern and interactive interface to upload files, run queries, and display results.  
⚡️ **SQLite (in-git initmemory):** Allows SQL query execution directly on the loaded data.  
⚡️ **Pandas:** Enables fast and flexible data manipulation.  
⚡️ **File Format Support:** Supports multiple formats like `CSV`, `Excel`, `Parquet`, and `JSON`.

---

##  How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yeuner/File-Analysis-SQL-Demo.git
   cd File-Analysis-SQL-Demo
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: .\env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the app:
   ```bash
   streamlit run main.py
   ```


