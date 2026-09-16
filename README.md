# 🚨 Customer Feedback Alert System

A Python automation project that analyzes customer feedback using ratings and keyword-based rules to automatically identify customers who require attention.

The system classifies feedback as **OK**, **WARNING**, or **CRITICAL**, filters actionable feedback, and generates an automated alert report.

## 🚀 Features

- Processes multiple customer feedback records automatically
- Uses customer ratings and keyword detection
- Detects critical issues such as fraud, unauthorized charges, and account security concerns
- Classifies feedback as OK, WARNING, or CRITICAL
- Prioritizes critical issues over standard warnings
- Filters out feedback that does not require attention
- Generates an automated `customer_feedback_alerts.txt` report

## 🛠️ Technologies

- Python
- Google Colab
- Lists and dictionaries
- Conditional logic
- List comprehensions
- File automation

## ⚙️ How It Works

```text
Customer Feedback
        ↓
Python processes each record
        ↓
Rating + Keyword Analysis
        ↓
┌──────────┬──────────┬──────────┐
│    OK    │ WARNING  │ CRITICAL │
└──────────┴──────────┴──────────┘
        ↓
Filter actionable feedback
        ↓
Generate Alert Report
```

## 📝 Example Output

```text
CUSTOMER FEEDBACK ALERT REPORT
========================================

Customers requiring attention: 3

WARNING: Maya
Rating: 2/5
Feedback: My order arrived late and customer service never responded.
----------------------------------------

CRITICAL: Alex
Rating: 1/5
Feedback: I was charged twice! I need a refund immediately.
----------------------------------------

CRITICAL: Morgan
Rating: 1/5
Feedback: My account was hacked and I see unauthorized charges!
----------------------------------------
```

## 🧠 What I Learned

This project helped me practice:

- Building rule-based automation systems
- Processing structured data with Python
- Working with lists and dictionaries
- Keyword matching and text normalization
- Designing decision logic with `if`, `elif`, and `else`
- Filtering actionable records
- Prioritizing alerts by severity
- Automatically generating reports

## ⚠️ Limitations

This version uses predefined keyword rules. Feedback using unexpected language may not be classified correctly.

A future version could use an LLM or natural language processing model to understand customer intent and sentiment beyond exact keyword matches.

## 📁 Project Structure

```text
customer-feedback-alert-system/
├── customer_feedback_alert_system.ipynb
├── customer_feedback_alerts.txt
├── requirements.txt
├── .gitignore
└── README.md
```

## 👨‍💻 Author

Christopher Dameron
