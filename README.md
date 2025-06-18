# 💸 Telegram Shared Expense Tracker Bot

A Telegram bot built using **Node.js** and **MongoDB** to track and manage shared group expenses. Easily split costs, settle balances, and track who owes what — all from Telegram!

---

## 📁 Project Structure

```
Telegram-Expense-Tracker-Bot/
├── index.js             # Main bot logic
├── .env                 # Environment variables
├── package.json
└── README.md            # You're here!
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/officeboy12242/Telegram-Expense-Tracker-Bot.git
cd Telegram-Expense-Tracker-Bot
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env` file in the root directory:

```env
BOT_TOKEN=your_telegram_bot_token
MONGO_URI=your_mongodb_connection_string
```

- Get your bot token from [@BotFather](https://t.me/BotFather)
- Use MongoDB Atlas or a local MongoDB URI

---

## ▶️ Run the Bot

### For development (with auto-reload)

```bash
npx nodemon index.js
```

> Make sure you have nodemon installed globally. If not:

```bash
npm install -g nodemon
```

### For production

```bash
node index.js
```

---

## 🧪 Sample `.env` File

```env
BOT_TOKEN=123456789:ABCdefYourBotTokenHere
MONGO_URI=mongodb+srv://username:password@cluster0.mongodb.net/expense_bot?retryWrites=true&w=majority
```

---

## 🚀 Features

- ➕ Add new expenses
- 🤝 Split equally or assign full amount to someone
- 👥 Include or exclude payer in splits
- 📊 View balance summary
- ✅ Settle balances individually or all at once
- 📖 See full expense history
- 📱 Inline keyboard UI with Telegram buttons

---

## 🧹 To-Do Features

- ⏱ Monthly or weekly summary report
- 📦 Export to CSV/Excel
- 🔔 Notifications/reminders
- 🧠 Smart split suggestions

---

## 📸 Usage Flow

1. Start bot with `/start`
2. Choose to split or assign owed expense
3. Enter amount, description, and participants
4. Confirm and record
5. Use “Settle” to view and clear balances

---

## 🤝 Contributing

Contributions are welcome!  
Please fork this repo and submit a pull request for improvements or feature suggestions.

---
