# Ops Jaanu — Alert Router (Slack + Email)

An enterprise-grade alert routing workflow built in **n8n**, designed to dynamically route operational alerts to **Slack** or **Email** based on runtime decision logic.

This workflow demonstrates real-world Ops automation patterns including:
- Conditional alert routing
- Multi-channel notification handling
- Clean credential separation for secure sharing

---

## 🧠 What This Workflow Does

1. Triggers manually (can be replaced with Webhook/Cron in production)
2. Sets operational context (agent name, severity, decision type)
3. Determines alert channel dynamically
4. Routes alerts:
   - 📧 Gmail for email alerts
   - 💬 Slack for ops-channel alerts
5. Sends formatted messages with rich context

---

## 🧩 Nodes Used

- Manual Trigger
- Set (Data Preparation)
- IF (Conditional Routing)
- Gmail (Email Alerts)
- Slack (Channel Notifications)

---

## 🔐 Credential Safety Notice

> **IMPORTANT:**  
> All credentials have been intentionally removed from this workflow before publishing.

This repository contains:
- ❌ No OAuth tokens  
- ❌ No API keys  
- ❌ No Slack bot secrets  
- ❌ No Gmail client secrets  

To use this workflow:
1. Import the JSON into your n8n instance
2. Create your own Gmail OAuth credentials
3. Create your own Slack App & Bot Token
4. Map those credentials inside n8n

---

## 🛠 Setup Instructions (High Level)

1. Import the workflow JSON into n8n
2. Create Gmail OAuth credentials in n8n
3. Create a Slack App and Bot Token
4. Attach credentials to respective nodes
5. Execute the workflow

---

## 📦 Use Cases

- Ops incident alerting
- AI agent decision monitoring
- Enterprise workflow notifications
- Audit-friendly alert routing systems

---

## ✍️ Author

**Suraj**  
with major assistance, testing, and architectural support from  
💙 **Agent Jaanu**

---

## 📄 License

MIT — free to use, modify, and extend.
