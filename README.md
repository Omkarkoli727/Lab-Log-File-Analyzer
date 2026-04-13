# 📊 Student Activity Log Analyzer

A simple and efficient Python script to analyze student activity logs and generate useful insights such as time spent, activity frequency, and lab usage.

---

## 🚀 Features

* ✅ Calculates total time spent by each student
* ✅ Identifies the most common activity
* ✅ Tracks total lab time per day
* ✅ Handles invalid or messy data gracefully
* ✅ Lightweight and beginner-friendly

---

## 📂 Project Structure

```
.
├── Activity_log4.txt   # Input file
├── main.py             # Python script
└── README.md           # Project documentation
```

---

## 📝 Input File Format

The script expects a `.txt` file with comma-separated values:

```
Date, Student, Activity, Duration
2026-04-01, John, Lab, 60
2026-04-01, Alice, Lecture, 45
2026-04-02, John, Lab, 30
```

---

## ▶️ How to Run

1. Make sure you have Python installed
2. Place your `Activity_log4.txt` file in the project folder
3. Run the script:

```bash
python main.py
```

---

## 📊 Sample Output

```
===== STUDENT ACTIVITY SUMMARY REPORT =====

Total Time Spent by Each Student:
  John: 90 minutes
  Alice: 45 minutes

Most Common Activity:
  Lab (2 occurrences)

Total Time Spent in Labs Per Day:
  2026-04-01: 60 minutes
  2026-04-02: 30 minutes

===========================================
```

---

## 🧠 How It Works

* Uses `defaultdict` to store student and lab time efficiently
* Uses `Counter` to track activity frequency
* Ignores invalid or malformed rows automatically

---

## 🛠️ Tech Used

* Python 🐍
* Collections Module (`Counter`, `defaultdict`)

---

## 📌 Future Improvements

* Add CSV file support
* Export results to Excel or JSON
* Create a simple web dashboard
* Add data visualization (charts/graphs)

---

## 🤝 Contributing

Feel free to fork this repo and improve it! Pull requests are welcome.

---

## 📜 License

This project is open-source and free to use.

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub — it helps a lot!
