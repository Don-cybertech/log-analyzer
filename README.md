# 🔐 Log Analyzer

⚠️ This project simulates a Security Operations Center (SOC) log analysis workflow using real authentication logs.
It demonstrates automated threat detection, log parsing, and reporting in a Python environment.

# 📌 Overview

The Log Analyzer is a Python-based cybersecurity tool designed to analyze authentication logs and detect suspicious activities such as brute-force attacks, failed login attempts, and anomalous access patterns.

# This project reflects a real-world SOC workflow, including:

Log ingestion
Event parsing
Threat detection
Report generation

# ⚙️ Features

🔍 Authentication log parsing
🚨 Detection of suspicious login attempts
📊 JSON report generation (report.json)
🖥️ Command-line interface support
✅ Clean execution with status reporting

# 🛠️ Tech Stack
Python 3
argparse (CLI handling)
json (report generation)
re (log parsing with regex)

# 📁 Project Structure
log-analyzer/
│── logs/
│    └── sample_auth.log
│── screenshots/
│    ├── terminal_output.png
│    ├── json_report.png
│── log_analyzer.py
│── report.json
│── requirements.txt
│── README.md

# ▶️ Usage
🔹 Command Executed
python log_analyzer.py --file logs/sample_auth.log

# 📊 Real Execution Output
[INFO] JSON report generated: report.json

[INFO] No suspicious activity detected.

Process finished with exit code 0

# 📄 Generated Report (Actual Behavior)

After execution, the tool generates:

📁 report.json

This file contains structured log analysis results such as:

{
  "status": "success",
  "message": "No suspicious activity detected",
  "suspicious_activity": false
}

# 📸 Screenshots (Real Evidence)
🔹 Terminal Execution




👉 Shows successful execution and detection result

# 🔹 JSON Report Output




👉 Confirms structured report generation for SOC analysis

# 🧠 Detection Logic

The analyzer applies rule-based detection to identify potential threats:

🚫 Multiple failed login attempts
👤 Invalid user authentication attempts
🌐 Repeated access from the same IP
⚡ Rapid login requests (potential brute-force behavior)

In this test case:

✔️ No malicious patterns were detected
✔️ Log file is considered clean
✔️ Detection system is functioning correctly

# 🧪 Test Scenario
📂 Input file: logs/sample_auth.log
🔍 Log type: Authentication logs
🧠 Detection result: No suspicious activity detected
📊 Output: JSON report successfully generated

# ⚡ Installation
git clone https://github.com/YOUR_USERNAME/log-analyzer.git
cd log-analyzer
pip install -r requirements.txt

# 🏁 What This Project Demonstrates
✅ Practical log analysis skills
✅ Understanding of SOC workflows
✅ Ability to build security automation tools
✅ Clean and professional Python scripting

# 👤 Author

Egwu Don Achema
Cybersecurity Analyst | Python Developer

📜 License

MIT License

⭐ Support

If you find this project useful, give it a ⭐ and connect!

🧠 Detection Logic

The analyzer applies rule-based detection to identify potential threats
