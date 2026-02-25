# 📧 Task Automation Using Python Scripts

##  Project Overview

This project demonstrates **automation using Python scripting** to perform a real-life repetitive task.
The system automatically extracts all email addresses from a text file and stores them in a separate output file without manual effort.

Automation helps improve productivity, reduce human errors, and efficiently process large datasets.

---

##  Objective

The main objective of this project is to automate the process of extracting email addresses from textual data using Python.

---

##  Key Concepts Used

* Python Programming
* File Handling
* Regular Expressions (Regex)
* Automation Techniques
* Exception Handling
* Logging System

---

##  Technologies Used

* Python
* Google Colab / VS Code
* `re` Module (Pattern Matching)
* `os` Module (File Operations)
* `datetime` Module (Logging)

---

##  Project Structure

```
Python_Automation_Task/
│
├── extractor.py        # Main automation script
├── input.txt           # Input text file
├── emails.txt          # Extracted emails (Output)
├── log.txt             # Execution log
└── README.md           # Project documentation
```

---

##  Working Process

1. The user provides a text file containing data.
2. The Python script reads the file.
3. Email addresses are detected using Regular Expressions.
4. Duplicate emails are removed automatically.
5. Unique email addresses are saved into an output file.
6. Execution details are recorded in a log file.

---

##  Input Example

```
Contact support@gmail.com
Admin admin@yahoo.com
HR hr@company.in
Duplicate support@gmail.com
```

---

##  Output Example

### emails.txt

```
support@gmail.com
admin@yahoo.com
hr@company.in
```

### log.txt

```
2026-02-26 - Extracted 3 emails
```

---

##  Features

* Automatic email extraction
* Duplicate removal
* Error handling
* Execution logging
* Fast and efficient automation
* Easy to use

---

##  How to Run the Project

### Step 1: Install Python

Ensure Python is installed on your system.

### Step 2: Install Required Library

```
pip install colorama
```

### Step 3: Run Script

```
python extractor.py
```

---

##  Applications

* Data preprocessing
* Email database creation
* Log file analysis
* Document automation
* Data cleaning tasks

---

##  Future Enhancements

* GUI-based automation tool
* Multiple file processing
* Scheduled automation
* Web scraping integration
* Cloud storage support

---

##  Conclusion

This project showcases how Python automation can simplify repetitive real-world tasks. By combining file handling and pattern matching techniques, the system efficiently extracts useful information automatically.

---

##  Author

**Bhumika Patil**

Python Internship Project

