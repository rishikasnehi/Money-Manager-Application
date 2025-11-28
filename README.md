# Money-Manager-Application 💰

`Money-Manager-Application` is a lightweight **C++ console-based personal finance manager** that helps users track their daily incomes and expenses. It stores financial transaction records in a text file and provides running balance summaries — a practical utility that showcases foundational C++ skills like file handling, object-oriented programming, and menu-driven user interaction. 🧠💻

Hi there! 👋 I’m **Rishika Snehi** — a passionate software developer who loves solving problems through code and building meaningful applications. I enjoy learning new technologies, applying them through projects, and continuously improving myself. 🚀 I’m always excited to collaborate and contribute to open-source!

---

## 📚 What This Project Does

- Lets users **add income or expense entries** via a simple text-menu interface.  
- Records each transaction persistently in a text file (so data remains across runs).  
- Maintains a **running balance** — so users can view how much they have earned, spent, and their current net balance.  
- Displays a **history of transactions**, allowing users to review past entries.  
- Helps practise core programming concepts: object-oriented design (classes, modular code), file I/O, menu-driven flow, and separation of concerns (header / CPP files).

---

## ✅ Lessons Learned / Skills Gained

- Built a **menu-driven system** in C++.  
- Applied **OOP principles** in a real-world-like project.  
- Implemented **file handling** for persistent data storage.  
- Wrote **clean and modular code**, separating declarations (headers) and definitions.  
- Practiced **version control** (Git & GitHub) and project organization.  
- Created a **useful console app** that solves a real personal problem (tracking finance).

---

## 🛠️ How to Run

```bash
git clone https://github.com/rishikasnehi/Money-Manager-Application.git
cd Money-Manager-Application

# Compile the program
g++ main.cpp MoneyManager.cpp classMoneyManager.cpp classT.cpp utils.cpp -o money-manager

# Run the application
./money-manager

