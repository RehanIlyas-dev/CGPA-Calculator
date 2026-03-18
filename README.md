<div align="center">

# 🎓 CGPA Calculator

 — A beautiful console-based Cumulative Grade Point Average (CGPA) Calculator built in C++

[![Language](https://img.shields.io/badge/Language-C++-blue?logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## 📋 About

It is a clean, colorful, and user-friendly console application that helps students calculate their **semester GPA** and **cumulative CGPA** across multiple semesters.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Colorful Output** | ANSI color-coded console for a visually appealing experience |
| 📚 **Multi-Semester Support** | Add up to 12 semesters with up to 15 courses each |
| ✅ **Input Validation** | Rejects invalid grades and credit hours with clear error messages |
| 📊 **Progress Bars** | Visual ASCII progress bars for GPA representation |
| 📝 **Report Cards** | Detailed per-semester report card with formatted tables |
| 🏆 **Academic Standing** | Automatic classification (Dean's List, Honor Roll, etc.) |
| 📈 **GPA Trend** | Semester-wise GPA comparison chart for multi-semester entries |
| 🔢 **Quality Points** | Displays individual course quality points and totals |

---

## 📖 Grade Scale

| Letter Grade | Grade Points |
|:---:|:---:|
| A+ / A | 4.0 |
| A- | 3.7 |
| B+ | 3.3 |
| B | 3.0 |
| B- | 2.7 |
| C+ | 2.3 |
| C | 2.0 |
| C- | 1.7 |
| D+ | 1.3 |
| D | 1.0 |
| F | 0.0 |

---

## 🚀 How to Run

### Prerequisites
- A C++ compiler (g++, clang++, or MSVC)

### Steps

| Step | Platform | Command |
|:----:|----------|--------|
| 1 | **Linux / Mac** | `g++ CGPACalculator.cpp -o CGPACalculator` |
| 2 | **Linux / Mac** | `./CGPACalculator` |
| 1 | **Windows** | `g++ CGPACalculator.cpp -o CGPACalculator.exe` |
| 2 | **Windows** | `CGPACalculator.exe` |

> **Note:** For best color support on Windows, use **Windows Terminal** or **VS Code integrated Terminal**

---

## 🧮 How CGPA is Calculated

| Formula | Expression |
|---------|------------|
| **Quality Points** | Grade Points × Credit Hours |
| **Semester GPA** | Total Quality Points ÷ Total Credit Hours |
| **CGPA** | Grand Total Quality Points ÷ Grand Total Credit Hours |

---

## 🏅 Academic Standing

| CGPA Range | Standing |
|:---:|---|
| ≥ 3.70 | 🌟 Dean's List (Outstanding!) |
| ≥ 3.50 | ⭐ Honor Roll (Excellent!) |
| ≥ 3.00 | ✅ Good Standing |
| ≥ 2.00 | 📝 Satisfactory |
| < 2.00 | ⚠️ Academic Probation |

---

## 🛠️ Built With

- **Language:** C++
- **Libraries:** `<iostream>`, `<string>`, `<iomanip>` (standard library only)
- **Styling:** ANSI Escape Codes for terminal colors

---

## 👨‍💻 Author

**Rehan Ilyas**


## 📄 License

This project is licensed under the **[MIT License](LICENSE)** — you are free to use, modify, and distribute this project.

© 2026 [Rehan Ilyas](https://github.com/RehanIlyas-dev)
