# WhatsApp Automation Bot for Restaurants 🍽️

## 📌 Overview
An AI-powered WhatsApp bot that automates restaurant/tiffin orders.  
Built using **N8N, Gemini AI, Google Sheets, and WhatsApp Business API**.  
The bot takes orders, validates them against inventory, saves them in a database, and replies instantly like a digital waiter.

## 🚀 Features
- 🤖 Smart conversational replies with **Gemini AI**
- 📝 Context memory (remembers user details & past messages)
- 📊 Google Sheets integration for Inventory, Orders, FAQs
- ✅ Validates menu items before confirming orders
- 📱 WhatsApp Business API for real-time customer interaction
- 🌐 Multi-language support (English, Hindi, Bengali, etc.)

## 🛠️ Tech Stack
- [N8N](https://n8n.io/) – Automation workflows
- [Gemini AI](https://ai.google/) – Conversational AI
- Google Sheets API – Database for orders & inventory
- WhatsApp Business API – Messaging platform

## 📂 Files
- `workflow.json` → Exported N8N workflow
- `sample_inventory.xlsx` → Example data for menu, orders, FAQ
- `screenshots/` → Bot demo screenshots (optional)

## 📖 Setup Guide
1. Import `workflow.json` into your N8N instance
2. Configure Gemini AI credentials (API Key)
3. Connect your Google Sheets with Inventory, Orders, and FAQ
4. Setup WhatsApp Business API (Meta Developer Account)
5. Start workflow → Send “Hi” on WhatsApp → Get bot reply

## 🎯 Business Impact
- Reduced manual errors in order-taking ✅  
- Saved time for restaurant/tiffin owners ⏳  
- 24/7 automated customer service 🚀  



