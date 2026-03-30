<div align="center">

# 🤖 OVERTAKE AI
### Automated Newsletter & Intel Pipeline

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-orange?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4-412991?style=for-the-badge)
![Tavily](https://img.shields.io/badge/Tavily-News%20Search-blue?style=for-the-badge)
![Slack](https://img.shields.io/badge/Slack-Trigger-4A154B?style=for-the-badge)
![Gmail](https://img.shields.io/badge/Gmail-Delivery-EA4335?style=for-the-badge)
![Telegram](https://img.shields.io/badge/Telegram-Notifications-26A5E4?style=for-the-badge)

> Two production-ready AI automation pipelines that eliminate
> manual newsletter creation and competitor research completely.

</div>

---

## 🚀 What This Does

| 🗞️ Pipeline 1 | 📊 Pipeline 2 |
|----------------|----------------|
| AI Newsletter Generator | Daily Intel Report |
| Triggered via Slack command | Runs automatically every day |
| Searches latest news with Tavily | Fetches competitor + industry feeds |
| Generates newsletter with OpenAI | Finds content gaps with AI |
| Sends to Gmail + Telegram + SMS | Sends report to Gmail + Slack + Sheets |

---

## 🗞️ Pipeline 1 — AI Newsletter Generator
```
Slack Command → Webhook → Extract Query → Topic Router
→ Code JS → Tavily Search → Format Results
→ Article Writer → Parse Output
→ Gmail + Slack + Telegram + SMS
```

### ❓ Problem
Manually researching and writing newsletters
takes hours every week.

### ✅ Solution
Send one Slack command and the pipeline does everything.

### ⚙️ How it works

| Step | Node | Action |
|------|------|--------|
| 1 | Webhook | Receives Slack command |
| 2 | Extract Slack Query | Extracts topic from command |
| 3 | Topic Router | Categorizes the request |
| 4 | Code in JavaScript | Parses and structures query |
| 5 | Tavily News Search | Searches latest news |
| 6 | Format Search Results | Structures the data |
| 7 | Article Writer | OpenAI generates newsletter |
| 8 | Parse Article Output | Formats the content |
| 9 | Send Newsletter Email | Delivers via Gmail |
| 10 | Send Campaign Report | Notifies via Slack |
| 11 | Telegram | Sends via Telegram |
| 12 | Send a Text Message | SMS notification |

### 💬 Usage
```
/newsletter topic=AI Agents 2026
/newsletter topic=Tesla layoffs
/newsletter topic=India startup funding
/newsletter topic=OpenAI GPT-5 release
```

---

## 📊 Pipeline 2 — Daily Intel Report
```
Schedule Trigger → Fetch Competitor Content
→ Fetch TNW + VentureBeat + Rundown AI
→ Prepare Feed Data → AI Gap Finder
→ AI Writer → Gmail + Slack + Sheets
```

### ❓ Problem
Keeping up with competitors and industry
news manually every day is exhausting.

### ✅ Solution
Runs automatically every day without
any manual input needed.

### ⚙️ How it works

| Step | Node | Action |
|------|------|--------|
| 1 | Schedule Trigger | Fires automatically daily |
| 2 | Fetch Competitor Content | Scrapes competitor sites |
| 3 | Fetch TNW Feed | Gets TNW news feed |
| 4 | Fetch VentureBeat Feed | Gets VentureBeat feed |
| 5 | Fetch Rundown AI | Gets Rundown AI feed |
| 6 | Prepare Feed Data | Combines all sources |
| 7 | AI Gap Finder | Finds content opportunities |
| 8 | AI Writer | Generates intel report |
| 9 | Code in JavaScript | Structures the output |
| 10 | Send Newsletter | Delivers via Gmail |
| 11 | Send Intel Report | Sends to Slack |
| 12 | Log Edition | Logs in Google Sheets |

---

## 🔧 Tech Stack

| Tool | Purpose | Type |
|------|---------|------|
| ![n8n](https://img.shields.io/badge/n8n-orange?style=flat-square) | Workflow Automation | Platform |
| ![Tavily](https://img.shields.io/badge/Tavily-blue?style=flat-square) | Real-time News Search | API |
| ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) | Content Generation | AI Model |
| ![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square) | Email Delivery | Communication |
| ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square) | Trigger + Notifications | Communication |
| ![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square) | Message Delivery | Communication |
| ![Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square) | Logging + Tracking | Storage |

---

## 🛠️ Setup Instructions

### Prerequisites
- ✅ n8n instance (cloud or self-hosted)
- ✅ Tavily API key → [app.tavily.com](https://app.tavily.com)
- ✅ OpenAI API key → [platform.openai.com](https://platform.openai.com)
- ✅ Gmail connected to n8n
- ✅ Slack webhook configured
- ✅ Telegram bot token

### Steps
```
1. Open n8n
2. Build the workflow from scratch
3. Add your API credentials
4. Configure Slack webhook
5. Activate workflow
6. Send /newsletter topic=Your Topic in Slack
```

---

## ✅ Assignment Checklist

- [x] 🗞️ Pipeline 1 — Newsletter Generator built
- [x] 📊 Pipeline 2 — Daily Intel Report built
- [x] 🛡️ Error handling added
- [x] 🗒️ Sticky notes added to workflow
- [x] 🎥 Screen recording completed
- [x] 💻 GitHub repo created
- [x] 📣 Skool post published

---

<div align="center">

## 👤 Author

**govardhan**

Batch-6 | Week-5 Assignment | Social Eagle AI Program

![](https://img.shields.io/badge/Social%20Eagle%20AI-Batch%206-red?style=for-the-badge)
![](https://img.shields.io/badge/Week-5-blue?style=for-the-badge)
![](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)

</div>
