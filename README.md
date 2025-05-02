# 💻 Email Telegram Notifier

Email Telegram Notifier is a lightweight desktop application that automatically monitors your email inbox and sends instant Telegram alerts whenever a new message arrives from a specified sender. Designed for simplicity and reliability, this tool bridges your email and Telegram channels to ensure you never miss important emails — even when you're away from your inbox.
 
---

## 📦 Features

- Supports IMAP email monitoring (e.g., Gmail, cPanel, Outlook)

- Instant Telegram bot alerts for selected sender(s)

- Custom sender filters and keywords

- Configuration and logs are saved automatically

- Simple GUI for setup, no technical knowledge required

- Can be packaged as a standalone .exe (no need to install Python)

---

## 🖥 How to Use

### ✅ 1. Download and Run the App

- Download `run.exe`.
- Double-click to run it.
- A browser window will open automatically with the interface.

---

### ⚙️ 2. Insert the Config

To insert config (like email, Telegram credentials, sender filters, etc.):

1. On the **landing page**, click on **“Insert Config”** or similar input fields.
2. Enter all required fields such as:
   - IMAP server (`mail.example.com`)
   - Email (`you@example.com`)
   - Telegram Bot Token and Chat ID
3. Click **Save**.
4. You will see a popup message like `✅ Config saved successfully` if it works.

> ❗ Make sure the config is entered **before clicking Start**, otherwise you'll see `❌ No config data, insert data first`.

---

### 🔄 3. Application Workflow

1. Insert your config
2. Press **Start**
3. The app begins checking the email inbox periodically
4. When a message from a matching sender is found, a Telegram notification is sent
5. Logs are shown in the GUI and saved locally

---
 
