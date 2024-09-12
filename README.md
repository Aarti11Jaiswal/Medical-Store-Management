# Medical-Store-Management

Project Overview
The Medical Store Management System is a Python-based project that automates the process of managing a medical store's inventory, staff records, and billing. This system uses a MySQL database for backend storage, providing a seamless way to manage medicine stock, generate customer bills, maintain staff information, and more. The project is designed with multiple options to help store managers streamline their operations efficiently.

Features
The system provides the following features:

About the Project
Displays a brief description of the project and its core components (Stock, Staff, and Bill tables).

List of All Medicines Available in Stock
Fetches and displays a list of all medicines currently available in the stock.

Display Medicines in Alphabetical Order
Sorts and shows the available medicines in alphabetical order.

Add New Medicine in Stock
Allows users to insert new medicine records into the stock by entering relevant details like medicine name, price, availability, manufacturer name, type, and composition.

Delete a Medicine from Stock
Removes a medicine from the stock if it is no longer available. The user can input the medicine's name, and the system will delete the corresponding record.

Show Details of All Bills
Displays all bill records generated for customers.

Make Customer Bill
Enables store personnel to record customer orders by adding the customer name, mobile number, and ordered medicine details (medicine name, quantity, and price).

Total Bill of Customer
Calculates and displays the total amount spent by a customer based on their mobile number.

Add New Staff Details
Allows the user to add new staff members by inputting their name, age, work profile, and mobile number.

Record of Staffs
Displays all the details of the staff members currently in the database.

Delete Staff Details
Removes staff records based on the staff name, in case a staff member leaves the store.

Exit
Allows the user to safely exit the program.

Technology Stack
Python: Used to build the application logic.
MySQL: Used for database storage to manage tables for medicines, staff, and bills.
Jupyter Notebook: Ideal for development, testing, and running the Python code interactively.
Database Structure
The project uses three main tables:

Stock: Stores details about the medicines, including Medicine_name, Price, Available_or_Not, Manufacturer_Name, Medicine_Type, Pack_size_label, and compositions.
Staff: Stores staff information, such as name, age, profile, and mobile_no.
Bill: Records all customer transactions, including Customer_Name, Mobile_No, Medicine_Name, Quantity, and Price.
How to Use
Clone the repository.
Set up a MySQL database with tables for stock, staff, and bill.
Connect the Python code with your MySQL database by setting up the cursor and connection objects.
Run the script in an environment like Jupyter Notebook or any Python IDE.
Choose from the menu to perform the desired operation such as adding medicines, generating bills, or managing staff records.
Error Handling
The project includes exception handling to ensure incorrect inputs or database errors are properly caught and displayed to the user.
Future Enhancements
Adding more detailed search filters for medicines and staff.
Implementing user authentication for better security.
Generating visual reports and analytics for store performance.
