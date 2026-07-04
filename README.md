# 🚀 Lead Management Automation with n8n

An automated Lead Management Workflow built with **n8n**, **Google Sheets**, **Gmail**, and **Telegram**.

This workflow automatically monitors new leads submitted through Google Forms, evaluates their priority based on the estimated budget, updates Google Sheets, and instantly sends email and Telegram notifications for high-priority leads.

---

# 📌 Features

- ✅ Automatically detects new leads from Google Sheets
- ✅ Processes only the latest submitted lead
- ✅ Checks lead priority using IF conditions
- ✅ Updates Lead Status and Priority automatically
- ✅ Sends a beautifully formatted HTML email
- ✅ Sends instant Telegram notifications
- ✅ Fully automated with n8n

---

# ⚙️ Workflow

```text
Google Form
      │
      ▼
Google Sheets
      │
      ▼
Google Sheets Trigger
      │
      ▼
Get Latest Lead
      │
      ▼
High Priority Check
      │
 ┌────┴────┐
 │         │
True      False
 │         │
 ▼         ▼
Update Sheet   Update Sheet
 │
 ▼
Gmail Alert
 │
 ▼
Telegram Alert
```

---

# 🛠 Tech Stack

- n8n
- Google Forms
- Google Sheets
- Gmail API
- Telegram Bot API
- JavaScript

---

# 📷 Screenshots

## Workflow

![Workflow](assets/workflow-overview.jpg)

## Gmail Notification

![Gmail](assets/email-demo.jpg)

## Telegram Notification

![Telegram](assets/telegram-demo.jpg)

---

# 📂 Project Structure

```text
lead-management-automation-n8n/
│
├── assets/
│   ├── workflow-overview.jpg
│   ├── email-demo.jpg
│   └── telegram-demo.jpg
│
├── docs/
├── workflow.json
├── README.md
└── LICENSE
```

---

# 🚀 Use Case

This automation is ideal for:

- Lead Management
- Sales Teams
- Digital Agencies
- AI Automation Agencies
- CRM Automation
- Business Process Automation

---

# 👨‍💻 Author

**Tasmiul**

AI Automation Freelancer

GitHub:
https://github.com/tasmiulpbn-cyber

---

⭐ If you found this project useful, consider giving it a star.S
## Workflow Overview

![Workflow](assets/workflow-overview.png)

---

## Email Notification

![Email](assets/email-demo.png)

---

## Telegram Notification

![Telegram](assets/telegram-demo.png)
