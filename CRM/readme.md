# AI CRM Automation with Google Sheets (n8n)

An automated CRM system built using n8n and Google Sheets to manage leads, track interactions, and streamline follow-ups with AI-powered workflows.

---

## 🚀 Overview

This project demonstrates how to build a lightweight CRM system using Google Sheets as a database and n8n for automation.

It helps businesses manage leads efficiently without relying on expensive CRM tools.

---

## 🧠 Problem

Managing leads manually can lead to:
- Missed follow-ups  
- Disorganized data  
- Time-consuming repetitive tasks  

Small businesses and creators often don’t need complex CRM software but still require structured lead management.

---

## 💡 Solution

This workflow automates the CRM process by:

- Storing leads in Google Sheets  
- Automatically updating lead status  
- Sending follow-up emails/messages  
- Using AI to generate personalized responses  
- Triggering workflows based on lead activity  

---

## ⚙️ Features

- 📥 Lead capture and storage (Google Sheets)
- 🔄 Automated follow-ups
- 🤖 AI-generated responses (OpenAI)
- 📊 Status tracking (New, Contacted, Converted)
- 🔔 Notifications via email/Telegram
- 🔗 API integrations

---

## 🧰 Tech Stack

- n8n (workflow automation)
- Google Sheets API
- OpenAI API
- Webhooks
- Email / Telegram integrations

---

## 📂 Project Structure

- `workflow.json` → n8n workflow file  
- `README.md` → Project documentation  
- `screenshots/` → Workflow visuals (optional)  

---

## ⚡ How It Works

1. Lead data is added via form/webhook or manually in Google Sheets  
2. n8n detects new entries or updates  
3. AI generates personalized responses  
4. Follow-up messages are sent automatically  
5. Lead status is updated based on interaction  

---

## 🛠️ Setup Instructions

1. Import `workflow.json` into n8n  
2. Connect your Google Sheets credentials  
3. Add your OpenAI API key  
4. Configure email/Telegram nodes  
5. Test the workflow with sample data  

---

## 🎯 Use Cases

- Freelancers managing client leads  
- Small businesses tracking prospects  
- Content creators handling brand deals  
- Sales automation for outreach  

---

## 📌 Notes

- Ensure all API credentials are configured properly  
- Customize the workflow based on your use case  
- Can be extended into a full CRM system with dashboards  

---

## 📬 Contact

For collaboration or automation ideas, feel free to reach out.
