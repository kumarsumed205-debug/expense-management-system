Expense Management System (Pocket Expense Tracker)
​Student: sumed kumar
Registration No: 25BAI10256
Department: BTech CSE AIML, Vellore Institute of Technology (VIT) Bhopal  
​Introduction
​The Pocket Expense Tracker is a lightweight, Python-based Command Line Interface (CLI) application designed to solve the problem of tracking personal finances. While many financial apps are bloated with features or require internet access, this tool provides a fast, distraction-free way to log, view, and analyze daily expenses.  
​The system focuses on speed, simplicity, and data persistence using CSV files, ensuring users stay in control of their data.  
​Features
​The system provides the following core functionalities:
​Add Expense: Accepts expense details (Category, Amount, Note) and automatically captures the current date. It validates numeric input to prevent errors.  
​View All Expenses: Displays a formatted table of all recorded expenses with serial numbers.  
​Category Filtering: Filters expenses based on user-provided categories (e.g., "Food") to show targeted spending.  
​Total Calculation: Computes and displays the grand total of all expenses logged in the system.  
​Delete Expense: Allows the user to remove an incorrect entry by selecting its index number from the list.  
​Data Persistence: Data is auto-saved to expenses.csv after every action to prevent data loss.  
​Technical Stack & Design
​Language: Python 3.  
​Storage: Local CSV file (expenses.csv) acts as the database. CSV was chosen over SQL for simplicity and portability.  
​Libraries Used: Standard Python libraries (os, csv, datetime) were selected to remove the need for complex dependency management.  
​Interface: CLI (Command Line Interface) chosen for lightweight performance over a GUI.  
​System Architecture
​The project follows a modular script structure:  
​main(): Handles the menu loop and user input.  
​Functions: Specific tasks like add_data(), view_list(), and calc_sum() are separated for clarity.  
​File Handling: Uses file appending modes for safe saving of data.  
​How to Run
​Ensure Python 3 is installed on your system.  
​Clone or download the repository.
​Run the script. The application launches instantly and processes inputs without lag.  
​Navigate the simple text-based menu using number keys (1-6).  
​Menu Options
​Add New Expense
​View All Expenses
​See Total Spending
​View Category Wise
​Delete an Expense
​Exit App  
​Testing
​The system underwent specific testing to ensure reliability:
​Unit Testing: Verified that data correctly appends to the CSV.  
​Boundary Testing: Tested inputs with empty spaces and negative numbers.  
​Negative Testing: Intentionally entered text when the system asked for an amount to ensure error messages triggered correctly.  

​Future Enhancements
​Budget Alerts: Add a feature to set a monthly limit and warn the user if they cross it.  
​Visualization: Integrate matplotlib to show a pie chart of expenses by category.  
​GUI: Port the logic to a Tkinter or PyQt interface for a better user experience.  

