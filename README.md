# Telegram_Bot_N8N_Automation

Automate Telegram bot workflows using **n8n** — a powerful, open-source automation tool. Integrate your Telegram bot with workflows to send/receive messages, trigger actions, and build custom automations without complex code.

This project contains sample workflows, JSON export files, and assets to help you deploy Telegram automation using n8n.

---

## 🚀 Features

- 📩 **Receive & send Telegram messages** via n8n workflows  
- 🔄 **Trigger automated actions** from Telegram messages  
- 📦 Includes exported n8n workflow JSON files  
- 📸 Example screenshots & demo video for reference  
- ⚙️ Configurable for your bot’s use cases

---

## 📁 Repository Structure

```

📦 Telegram_Bot_N8N_Automation
├── 📸 screenshots/           # Visual references for workflows/UI
├── 🎥 video/                 # Demo video(s)
├── Load_Data_Flow.json       # n8n workflow export for core automation
├── Telegram_Bot.json         # n8n workflow export for Telegram bot setup
├── .gitignore
└── README.md                 # This file

````

---

## 🧠 About n8n + Telegram Integration

This repository leverages **n8n’s Telegram integration** to automate interactions with a Telegram bot. n8n supports triggering workflows on incoming messages and performing actions such as sending replies, handling media, and more using Telegram’s Bot API.:contentReference[oaicite:0]{index=0}

To connect a Telegram bot with n8n:

1. Create your bot using **BotFather** in Telegram.
2. Copy the bot’s **API token**.
3. Add Telegram **credentials** in n8n (via n8n → Credentials).:contentReference[oaicite:1]{index=1}
4. Import the provided workflow JSON files into your n8n instance.

---

## 📥 Import Workflows

1. Open your n8n instance.
2. Go to **Workflows → Import from file**.
3. Select `Telegram_Bot.json` and/or `Load_Data_Flow.json`.
4. Update credentials (Telegram Bot API token, etc.).
5. Save & activate the workflow!

---

## ⚙️ Setup Instructions

### 1. Create Telegram Bot  
Use **BotFather** on Telegram:
```sh
/newbot
````

Follow the prompts to get your **bot token**.([n8n Blog][1])

---

### 2. Configure n8n

* Start your n8n (cloud or self-hosted).
* Go to **Credentials → Telegram API**.
* Enter your bot token and save.

n8n’s Telegram nodes support multiple operations including:

* Sending messages
* Editing messages
* Sending media
* Responding to triggers
  (These options are configurable inside each workflow’s nodes.)([n8n Docs][2])

---

## 📝 Example Use Cases

✅ Auto-reply to Telegram commands
✅ Forward messages to other systems
✅ Trigger internal business processes from chats
✅ Send media or automated notifications

---

## 📸 Screenshots & Demo

See the **screenshots** and **video** folders for visual walkthroughs of the workflow and how automation works in action.

---

## 🛠️ Customize

You can extend workflows by:

* Adding more Telegram triggers (text, commands, media)
* Integrating other services (Google Sheets, Webhooks, APIs)
* Including conditional logic for replies

Explore n8n nodes and templates to expand functionality.

---

## 🤝 Contributing

Contributions are welcome!
To contribute:

1. Fork the repository
2. Create a feature branch
3. Add your enhancements
4. Submit a PR

---

## 📜 License

This project is open-source — feel free to use and modify it.

---

## ❤ Thanks

Powered with n8n and Telegram Bot integrations — automate your conversations and workflows with ease!

```
