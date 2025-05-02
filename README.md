# 💻 Email Telegram Notifier

Email Telegram Notifier is a lightweight desktop application that automatically monitors your email inbox and sends instant Telegram alerts whenever a new message arrives from a specified sender. Designed for simplicity and reliability, this tool bridges your email and Telegram channels to ensure you never miss important emails — even when you're away from your inbox.
 
---

## 📦 Features

- Supports IMAP email monitoring (e.g., Gmail, cPanel, Outlook)

- Instant Telegram bot alerts for selected sender(s)

- Custom sender filters and keywords

- Configuration and logs are saved automatically

- Simple GUI for setup, no technical knowledge required


---

## 🖥 How to Use

### ✅ 1. Download and Run the App

- Download `run.exe`.
- Double-click to run it.
- A GUI will open automatically with the interface.

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

## 🤖 How to Create a Telegram Bot

Follow these steps to connect your Telegram bot:

### Step 1: Create the Bot
1. Open Telegram, search for **@BotFather**
2. Type `/newbot` and follow the steps:
   - Set a **bot name** (e.g. Email Notifier)
   - Set a **username** (must end in `bot`)
3. BotFather gives you a **Bot Token**
5. Logs are shown in the GUI and saved locally

---

## 👥 Using the Bot in a Telegram Group (Optional)

If you want the bot to send messages to a **group** instead of just to you directly, follow these steps:

---

### ✅ Step 1: Create a Group
1. Open Telegram and click **New Group**
2. Add at least one member (can be just you for now)
3. Set a group name (e.g., `Email Alerts Group`)

---

### ✅ Step 2: Add the Bot to the Group
1. In the group, tap the **Group Name** → **Manage Group**
2. Select **Add Members** and search for your bot username (e.g., `@email_notify_bot`)
3. Add the bot to the group

---

### ✅ Step 3: Promote the Bot to Admin
1. Go to **Group Settings** → **Administrators**
2. Select your bot and tap **Promote to Admin**
3. Enable the following permissions:
   - ✅ Send Messages
   - ✅ Pin Messages (optional)
   - ❌ No need for delete/ban rights

---
 
