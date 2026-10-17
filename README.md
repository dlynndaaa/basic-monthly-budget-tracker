# 💰 Monthly Budget Tracker

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-Terminal-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white)

A simple C++ based CLI (Command Line Interface) program to track and manage monthly finances. This program helps record details of income, expenses, savings allocations, and calculates a final summary to determine the remaining balance at the end of the month.

## 📸 Output Screenshot
<img width="1920" height="3015" alt="outputBasicMonthlyBudgetTracker" src="https://github.com/user-attachments/assets/1f73620e-2292-4fd1-a74a-226e57739e67" />

## 🚀 Key Features
- **Income Tracking:** Records various income sources and their amounts.
- **Expense Tracking:** Tracks monthly expense details (transportation, food, personal needs, etc.).
- **Savings Allocation:** Allocates funds to various savings categories.
- **Summary:** Automatically calculates `Total Income`, `Total Expenses`, `Total Savings`, and `Total Left` (remaining balance).
- **Evaluation System (Notes):** Provides an automated message at the end of the program based on the remaining balance status (surplus or deficit).

## 🛠️ Programming Concepts Used
This program is built using several basic data structures and control flow concepts in C++:
- **Struct:** Used to group data entities (number, date, description, amount) in the income, expense, and savings tables.
- **Array:** Used to store a collection of strings such as table headers and summary titles.
- **Functions / Modularity:** Separates the UI/display logic such as `beranda()`, `headTable()`, and `judulSummary()` to make the code cleaner and easier to read.
- **Control Flow:** Uses `do-while` loops to repeat the program based on user input, and `if-else` statements for final validation logic.
- **I/O Manipulation:** Uses `iomanip` (`setw`) to format spacing for precise table output in the console.

## 💻 How to Run the Program (via Windows CMD)

1. Ensure a C++ compiler (MinGW/MSYS2) is installed and registered in your system's PATH.
2. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/dlynndaaa/Basic-Monthly-Budget-Tracker.git

## 💻 Cara Menjalankan Program (via CMD Windows)

1. Pastikan compiler C++ (MinGW/MSYS2) sudah terinstal dan terdaftar di sistem.
2. *Clone* repositori ini ke lokal:
   ```bash
   git clone https://github.com/dlynndaaa/Basic-Monthly-Budget-Tracker.git
3. Open the repository folder, then open the terminal/CMD.
4. Compile the C++ file:
   ```bash
   g++ MonthlyBudgetTracker-ProyekUAS-DelindaMegaPutri-TI-1A.cpp -o budget
5. Run the compiled program:
   ```bash
   budget

## 👤 Author
**Delinda Mega Putri**
- 🎓 Informatics Engineering, Universitas Muhammadiyah Sukabumi
- 💼 [LinkedIn](https://www.linkedin.com/in/dlnmgp)
- 📧 Email: delindamegaputri123@gmail.com
