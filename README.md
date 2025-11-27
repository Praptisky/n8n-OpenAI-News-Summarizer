# 🧠 n8n OpenAI News Summarizer Workflow

This repository contains an **n8n automation workflow** that uses **OpenAI** to fetch and summarize the latest news articles.  
It extracts relevant topics from trusted sources and provides short, concise, and easy-to-understand summaries.

---

## 🚀 Features

- Fetches current news using an API or RSS feed
- Uses OpenAI to summarize long article text
- Outputs daily or on-demand summaries
- Easily configurable and scalable
- Fully automated and runs in n8n

---

## 📂 Files Included

| File Name | Description |
|----------|-------------|
| `ai_agent_workflow.json` | Main workflow JSON that can be imported into n8n |

---

## 📥 How to Use

1. Install and run **n8n**
   - Cloud version ➜ https://app.n8n.io  
   - Local install ➜ https://docs.n8n.io/hosting/

2. Import the workflow:
   - Go to **n8n → Workflows → Import from File**
   - Select `ai_agent_workflow.json`

3. Add required credentials:
   - OpenAI API Key
   - RSS or News API (optional, depending on your configuration)

4. Execute the workflow to get summarized news!

---

## 🛠️ Tech Stack

- **n8n**
