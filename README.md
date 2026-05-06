# 📊 Student Activity Log Analyzer

A Python script that reads a student activity log file, analyzes the data, and generates a structured summary report in a new output file.

---

## 🚀 Features

* 📥 Accepts custom input file from user
* 📄 Automatically generates output file
* ⏱️ Calculates total time spent by each student
* 📊 Finds the most common activity
* 🧪 Tracks total lab time per day
* 🧹 Skips invalid or incorrect data safely

---

## 📂 Project Structure

```id="tree12"
.
├── main.py               
├── Activity_log4.txt    
├── Activity_log4_out.txt 
└── README.md
```

---

## 📝 Input File Format

```id="input99"
Date, Student, Activity, Duration
2026-04-01, Omkar, Lab, 60
2026-04-01, Vinitha, Lecture, 45
2026-04-02, Shashikant, Lab, 50
```

---

## ▶️ How to Run

```bash id="run22"
python main.py
```

```id="prompt77"
Enter input file name: Activity_log4.txt
```

---

## 📤 Output

```id="jjokku"
Activity_log4.txt → Activity_log4_out.txt
```

---

## 📊 Sample Output

```id="output33"
===== STUDENT ACTIVITY SUMMARY =====

Total Time by Students:
Omkar : 90 minutes
Shashikant : 45 minutes

Most Common Activity:
Lab (2 times)

Lab Time Per Day:
2026-04-01 : 60 minutes
2026-04-02 : 30 minutes

==================================
```

---

## 🧠 How It Works

* Uses `defaultdict`
* Uses `Counter`
* Ignores invalid data

---

## 🛠️ Tech Stack

* Python 🐍
* collections module

---

## ⚡ Future Improvements

* Add graphs
* Build web version
* Support CSV/Excel

---

## 👨‍💻 Author

**Omkar Koli**

