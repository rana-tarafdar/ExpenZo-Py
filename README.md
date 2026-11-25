# 💰 ExpenZo-Py — Student Expense Tracker (Python Edition)

> A simple and beginner-friendly desktop application for students to manage their income and expenses, built with Python and Tkinter.

## 📌 About the Project

**ExpenZo-Py** is the Python version of [ExpenZo](https://github.com/rana-tarafdar/ExpenZo), our web-based expense tracker built with HTML, CSS, and Vanilla JavaScript.

It is developed as a **Project-Based Learning (PBL)** project. It solves the same problem as the original: helping students keep track of their **income, expenses, available balance, and spending patterns** in one place. This time we build it as a desktop application, using Python.

Building the same idea in two languages helps us compare how the same logic (CRUD, calculations, validation, data storage) is written in JavaScript and in Python.

---

## 🎯 Objectives

- Track personal income and expenses.
- Calculate the available balance.
- Organize expenses into categories.
- Maintain transaction records.
- Provide useful spending information through analytics.
- Learn practical Python development and GUI programming.
- Compare the Python implementation with the JavaScript version.
- Learn how to work collaboratively using Git and GitHub.

---

## 👨‍🎓 Target Users

The primary target users are **students** who want a simple way to manage their day-to-day finances, without needing a browser or internet connection.

---

## ✨ Planned Features

### 🔐 User Access
- Simple login screen.
- Basic input checks for credentials.

### 💰 Income Management
- Add income with source, amount, and date.
- View income records.
- Edit income records.
- Delete income records.

### 💸 Expense Management
- Add expenses with amount, date, and description.
- Categorize expenses (Food, Travel, Books, Entertainment, etc.).
- Select payment method.
- Edit expenses.
- Delete expenses.

### 🏠 Dashboard
- Total income.
- Total expenses.
- Available balance.
- Recent transactions.
- Quick navigation to all features.

### 📊 Analytics & Reports
- Income vs. expenses summary.
- Category-wise spending.
- Monthly spending information.
- Simple charts (bar and pie) for spending visualization.

### 💾 Data Management
- Store data in local JSON files, so records persist between sessions.
- Export data to JSON or CSV.
- Future support for importing data from the JavaScript version.

---

## 🛠️ Technologies

- **Python 3** — Application logic
- **Tkinter** — Graphical user interface (built into Python)
- **JSON** — Data storage
- **Matplotlib** *(optional)* — Charts and analytics
- **Git & GitHub** — Version control and team collaboration

---

## 📁 Project Structure

```
ExpenZo-Py/
│
├── main.py                  # Entry point of the application
│
├── ui/
│   ├── login_window.py
│   ├── dashboard.py
│   ├── income_window.py
│   ├── expense_window.py
│   └── analytics_window.py
│
├── core/
│   ├── storage.py           # Read/write JSON data
│   ├── calculations.py      # Totals, balance, category sums
│   ├── validation.py        # Input checking
│   └── utils.py             # Helper functions
│
├── data/
│   ├── categories.json
│   └── transactions.json
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ▶️ How to Run

1. Install Python 3.9 or above.
2. Clone the repository:
   ```bash
   git clone https://github.com/rana-tarafdar/ExpenZo-Py.git
   cd ExpenZo-Py
   ```
3. Install the optional dependencies (only needed for charts):
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python main.py
   ```

---

## 🔄 ExpenZo (JavaScript) vs ExpenZo-Py (Python)

| Aspect | ExpenZo (JavaScript) | ExpenZo-Py (Python) |
| ------ | -------------------- | ------------------- |
| Type | Web application | Desktop application |
| Interface | HTML + CSS | Tkinter |
| Logic | Vanilla JavaScript | Python |
| Data storage | Browser LocalStorage | Local JSON files |
| Charts | Browser-based visuals | Matplotlib |
| Runs on | Any web browser | Any system with Python |

---

## 👥 Team

| Member            | Role        |
| ----------------- | ----------- |
| **Rana Tarafdar** | Team Leader |
| **Rajdeep**       | Team Member |
| **Taukir**        | Team Member |
| **Akanshu**       | Team Member |
| **Abhradeep**     | Team Member |

### GitHub Profiles

- [Rana Tarafdar](https://github.com/rana-tarafdar)
- [Rajdeep](https://github.com/rajdeepbanerjeesp-star)
- [Taukir](https://github.com/taukir666sabri)
- [Akanshu](https://github.com/akanshumallick2007-hash)
- [Abhradeep](https://github.com/Abhradeep1711)

---

## 🌱 Learning Goals

Through this project, the team aims to gain practical experience in:

- Python fundamentals
- Functions, modules, and project structure
- Lists, dictionaries, and JSON handling
- File handling
- GUI programming with Tkinter
- Input validation and error handling
- CRUD operations
- Data calculations and basic data visualization
- Git and GitHub
- Team-based software development

---

## 🚧 Project Status

**Currently in development.**

The project is being built step by step: first the core logic (storage, calculations, validation), then the Tkinter screens, and finally analytics and export features.

---

## 📚 Project Type

**Project-Based Learning (PBL)**

This project is created for educational purposes to develop practical programming and teamwork skills.

---

## 📄 License

This project is developed for educational purposes.
