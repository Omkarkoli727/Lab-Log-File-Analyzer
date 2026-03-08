# 📊 Student Activity Log Analyzer

A Python script that analyzes a student activity log and generates a summary report.

The program reads an activity log file and calculates:

* Total time spent by each student
* Most common activity
* Total time spent in labs per day

## ✨ Features

* Parses activity log text files
* Calculates student activity durations
* Identifies the most frequent activity
* Summarizes lab usage per day
* Handles invalid or incomplete rows safely

## 📁 File Format

The input file should be a comma-separated text file with the following format:

```id="6as29v"
Date, Student, Activity, Duration
2026-03-01, Omkar, Lab, 40
2026-03-01, Rahul, Lecture, 60
2026-03-02, Omkar, Lab, 30
```

Fields:

* **Date** – Activity date
* **Student** – Student name
* **Activity** – Type of activity (Lab, Lecture, etc.)
* **Duration** – Time spent in minutes

## ⚙️ How It Works

The script reads the log file line by line and uses Python collections:

* `defaultdict` to track total time per student
* `Counter` to count activity frequency

It then generates a summary report.

## ▶️ Running the Script

1. Make sure Python is installed.
2. Place the activity log file in the same folder as the script.
3. Run the script:

```id="d7q3pd"
python activity_analyzer.py
```

## 🖥️ Example Output

```id="q9o41k"
===== STUDENT ACTIVITY SUMMARY REPORT =====

Total Time Spent by Each Student:
  Omkar: 120 minutes
  Rahul: 60 minutes

Most Common Activity:
  Lab (5 occurrences)

Total Time Spent in Labs Per Day:
  2026-03-01: 70 minutes
  2026-03-02: 50 minutes
```

## 🛠️ Technologies Used

* Python
* collections module (`Counter`, `defaultdict`)

## 👨‍💻 Author

Omkar Koli
