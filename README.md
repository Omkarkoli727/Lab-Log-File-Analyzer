📊 Student Activity Log Analyzer

A Python-based tool that reads a student activity log file, analyzes the data, and generates a summary report saved to a new output file 📄.

🚀 Features

✨ Reads activity logs from a user-provided file
📊 Calculates total time spent by each student
📌 Identifies the most common activity
🧪 Tracks total lab time per day
📁 Automatically generates an output report file
🛡️ Skips invalid or incomplete data safely

📂 Input Format

The input file must be a comma-separated text file:

Date, Student, Activity, Duration
2026-03-01, Omkar, Lab, 40
2026-03-01, Rahul, Lecture, 60
2026-03-02, Omkar, Lab, 30
▶️ How to Run
1️⃣ Run the script
python activity_analyzer.py
2️⃣ Enter input file name
Enter input file name: activity.txt
📄 Output

The program automatically creates an output file:

activity_out.txt
🖥️ Example Output File Content
===== STUDENT ACTIVITY SUMMARY =====

Total Time by Students:
Omkar : 120 minutes
Rahul : 60 minutes

Most Common Activity:
Lab (5 times)

Lab Time Per Day:
2026-03-01 : 70 minutes
2026-03-02 : 50 minutes

==================================
⚙️ How It Works
Uses defaultdict to track total time per student
Uses Counter to calculate most frequent activity
Processes file line-by-line for efficiency
Automatically ignores:
Empty lines
Header row
Invalid data
🧠 Use Cases

🎓 Student activity tracking
🏫 Lab usage monitoring
📊 Data analysis practice project
💼 Beginner-friendly Python project for portfolios

🛠️ Tech Stack
🐍 Python
📦 collections module (Counter, defaultdict)
🔮 Future Improvements
Add CLI arguments instead of input()
Export to CSV / Excel
Add data visualization 📈
Build a web interface

👨‍💻 Author
Omkar Koli
