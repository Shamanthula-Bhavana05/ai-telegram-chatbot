# -AI-Powered-Telegram-Chatbot-Using-n8n-Google-Gemini-Full-Automation-Workflow
AI-powered Telegram Chatbot built using n8n, Google Gemini LLM, and Simple Memory. Supports Multi-User Mode and Authorized-User Mode, provides real-time responses, persistent memory, and a fully automated workflow. Perfect for support systems, automation tasks, and intelligent conversational tools.

A fully automated and intelligent **Telegram Chatbot** built using **n8n**, **Google Gemini LLM**, and **Simple Memory**.
This chatbot supports **Multi-User Mode** (open access) and **Authorized-User Mode** (restricted access), offering real-time responses, persistent memory, and complete workflow automation.

---

## 📽 **Demo Video**

▶️ **YouTube:** [https://youtu.be/HxwK0Bk5cC4](https://youtu.be/HxwK0Bk5cC4)

---

## 🌐 **Connect With Me**

🔗 **LinkedIn:** [www.linkedin.com/in/shamanthula-bhavana-7343bb331](http://www.linkedin.com/in/shamanthula-bhavana-7343bb331)

---

## 🚀 **Features**

* 🔹 Real-time AI responses via Telegram Trigger
* 🔹 Intelligent conversations using Google Gemini LLM
* 🔹 Memory-enabled chat with Simple Memory node
* 🔹 Multi-User Mode – anyone can use the bot
* 🔹 Authorized-User Mode – restricted, secure access
* 🔹 Fully automated workflow inside n8n
* 🔹 Suitable for support systems, education & internal tools

---

## 🧠 **Architecture Overview**

* Telegram Bot API receives messages
* n8n workflow processes data
* Google Gemini LLM generates dynamic responses
* Simple Memory Node stores user context
* Authorization logic manages access
* Telegram Node sends replies back to users

---

## 🖼 **Workflow Image**

## 🖼 **Workflow Image**

![AI Mentor Chatbot](C:/Users/bhava/OneDrive/Desktop/Innomatics/Agentic_AI/AI Mentor Chatbot (Telegram and n8n)/AI Mentor Chatbot Image.png)

---

## 🛠 **Tech Stack**

* **n8n Automation Platform**
* **Google Gemini LLM**
* **Telegram Bot API**
* Simple Memory Node
* AI Agent Node

---

## 🔧 **Setup Instructions**

### **1️⃣ Create a Telegram Bot**

1. Open Telegram
2. Search for **@BotFather**
3. Run `/start` → `/newbot`
4. Save your **Bot Token**

---

### **2️⃣ Install & Run n8n**

You can install n8n using npm or Docker.

**Using npm:**

```bash
npm install -g n8n
n8n
```

**Using Docker:**

```bash
docker run -it --rm -p 5678:5678 n8nio/n8n
```

---

### **3️⃣ Import the Workflow**

1. Open **[http://localhost:5678](http://localhost:5678)**
2. Go to **Import Workflow**
3. Upload `workflow.json`

---

### **4️⃣ Add API Credentials**

Inside n8n, configure:

* Google Gemini API Key
* Telegram Bot API Token
* Simple Memory (Default config)

---

### **5️⃣ Run the Bot**

Send a message to your Telegram bot — the AI will respond instantly.

---

## 🧩 **How It Works Internally**

1. **Telegram Trigger** receives the message
2. **Authorization Block** checks user permission
3. **Simple Memory Node** retrieves stored context
4. **Gemini LLM Node** generates the AI response
5. **Memory Node** updates context
6. **Telegram Node** sends the final reply

---

## 🛡 **Modes Supported**

### 🔹 **Multi-User Mode**

Open access — anyone can chat with the bot.

### 🔹 **Authorized-User Mode**

Only selected user IDs can access the bot.
Useful for internal tools & secure workflows.

---

## 🎯 **Use Cases**

* AI-powered Support Systems
* Educational Bots
* Automated Query Handling
* Internal Team Assistants
* Personal Automation

---


