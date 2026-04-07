# 🛒 Supermarket Billing Queue System (C++)

A **D-Mart style Supermarket Billing System** developed in **C++** using Queue Data Structure (FIFO).  
This project simulates a real-world billing counter where customers are served in sequence, and bills are generated with GST calculation.

---

## 📌 Features

✨ Queue-based customer handling (FIFO)  
✨ Multiple items per customer  
✨ Automatic bill calculation  
✨ GST (18%) included  
✨ Professional receipt generation  
✨ File handling (records saved in `records.txt`)  
✨ Menu-driven console interface  

---

## 🧠 Concepts Used

- Queue (STL)
- Object-Oriented Programming (OOP)
- File Handling
- Structures & Classes
- Time & Date Handling
- Formatting using `iomanip`

---

## 🛠️ Tech Stack

- Language: **C++**
- Compiler: g++, CodeBlocks, VS Code

---

## ⚙️ How It Works

1. Customer enters billing queue  
2. Items are added (name, quantity, price)  
3. System calculates:
   - Subtotal  
   - GST (18%)  
   - Final Total  
4. Receipt is generated  
5. Data is stored in `records.txt`  

---

## 📸 Sample Output
=========== D-MART BILL ===========
Customer ID: 101
Name : Mahendra

Items:
Item Qty Price Total
Rice 2 50 100
Milk 1 30 30

Subtotal : 130
GST (18%): 23.4
TOTAL : 153.4

Date: Tue Apr 7 12:30:00 2026  



---


./billing


## 📂 File Structure

📁 Supermarket-Billing-System
┣ 📄 main.cpp
┣ 📄 records.txt
┗ 📄 README.md



---

## 🚀 How to Run

### 🔹 Step 1: Compile
```bash
g++ main.cpp -o billing


./billing
