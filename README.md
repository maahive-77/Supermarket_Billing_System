🛒 Supermarket Billing Queue System (C++)

A D-Mart style billing system developed in C++ using Queue (FIFO) and File Handling, designed to simulate real-world supermarket billing operations.

📌 Features
👥 Customer Queue Management (FIFO)
🛍️ Multiple Items per Customer
💰 Automatic Bill Calculation
🧾 GST Calculation (18%)
🖨️ Receipt Generation (Console Output)
📂 File Handling (Save records in records.txt)
📊 Structured Bill Format (like real supermarket)
🧠 Concepts Used
Queue Data Structure (STL)
Object-Oriented Programming (OOP)
File Handling (ofstream)
Dynamic Data Storage (vector)
Time & Date Handling (ctime)
⚙️ How It Works
Add Customer → Enter ID, Name, and Items
Items → Name, Quantity, Price
System calculates:
Subtotal
GST (18%)
Final Total
Customer is added to Queue
Serve Customer:
Generates Bill Receipt
Saves data to file
🧾 Sample Output
=========== D-MART BILL ===========
Customer ID: 101
Name       : Rahul

Items:
Item           Qty       Price     Total
Milk           2         50        100
Bread          1         40        40

Subtotal : 140
GST (18%): 25.2
TOTAL    : 165.2
Date: Tue Apr 07
==================================
📂 File Structure
📁 Supermarket-Billing-System
 ├── main.cpp
 ├── records.txt
 └── README.md
🚀 How to Run
🔧 Compile:
g++ main.cpp -o billing
▶️ Run:
./billing
📌 Future Enhancements
🖥️ GUI Interface (like real billing software)
🏪 Multiple Billing Counters
💳 Payment Methods (Cash/Card/UPI)
📦 Product Database Integration
📊 Sales Analytics Dashboard
🎯 Use Case

This project is ideal for:

🎓 BCA / B.Tech Students
💼 Mini Projects / Viva
🧪 Data Structure Practice
🏪 Retail System Simulation
🙋 Author

Mahendra
BCA Student | CCNA Certified
Passionate about Networking & Development

⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork it
📢 Share with others
📜 License

This project is open-source and free to use for educational purposes.
