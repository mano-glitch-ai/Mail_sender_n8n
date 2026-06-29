# 📧 Mail Sender - n8n Workflow

A simple email automation workflow built using **n8n**.

This workflow reads data from an RSS feed, filters the results, and sends relevant updates via Gmail.

---

## 🚀 Features

- Reads the latest items from an RSS feed
- Filters unwanted or irrelevant entries
- Automatically sends email notifications using Gmail
- Easy to customize for any RSS feed

---

## 🛠️ Workflow Overview

```
Manual Trigger
      │
      ▼
 RSS Feed Read
      │
      ▼
    Filter
      │
      ▼
 Gmail - Send Message
```

---

## 📂 Files

- `Mail_sender.json` – Exported n8n workflow

---

## ⚙️ Requirements

- n8n
- Gmail account with configured credentials
- Internet connection

---

## 📥 Importing the Workflow

1. Open n8n.
2. Click the **⋮** menu.
3. Select **Import from file**.
4. Choose `Mail_sender.json`.
5. Configure your Gmail credentials.
6. Update the RSS feed URL if needed.
7. Execute the workflow.

---

## 📧 How It Works

1. The workflow starts with a manual trigger.
2. It reads entries from an RSS feed.
3. A filter checks which entries should be processed.
4. Matching entries are emailed using Gmail.

---

## 🔧 Technologies Used

- n8n
- RSS Feed
- Gmail API

---

## 📜 License

This project is provided for educational purposes.
