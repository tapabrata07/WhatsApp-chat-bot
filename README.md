# AI WhatsApp Restaurant Order Chatbot

An end-to-end AI-powered WhatsApp chatbot automation system built using n8n, Google Gemini AI, WhatsApp Cloud API, and Google Sheets.

This chatbot automates customer interaction, food ordering, menu handling, FAQ responses, and order management in real time through WhatsApp.

---

# Features

## AI-Powered Conversations
- Uses Google Gemini AI for natural human-like replies
- Understands customer queries intelligently
- Handles multilingual and casual conversations

## WhatsApp Integration
- Real-time WhatsApp message automation
- Automatic message trigger and response system
- Works continuously after workflow activation

## Smart Menu Handling
- Reads live menu data from Google Sheets
- Displays available food items dynamically
- Checks stock availability automatically

## Order Management System
- Collects customer orders automatically
- Saves order details directly into Google Sheets
- Tracks ordered items and quantities

## FAQ Automation
- Answers frequently asked customer questions
- Handles pricing, availability, timings, and menu queries

## AI Memory Support
- Maintains conversational context
- Provides smoother and more natural chat experience

## No-Code AI Automation
- Built fully using n8n visual workflow automation
- No backend coding required
- Easy to scale and customize

---

# Tech Stack

- n8n Cloud
- Google Gemini AI
- WhatsApp Cloud API
- Google Sheets API
- AI Agent Node
- Simple Memory Node

---

# Workflow Architecture

```txt
WhatsApp Message
        ↓
WhatsApp Trigger
        ↓
AI Agent (Gemini AI)
        ↓
Inventory / FAQ / Order Tools
        ↓
Google Sheets Storage
        ↓
Automated WhatsApp Reply
```

---

# Use Cases

- Restaurant order automation
- AI customer support
- Food delivery businesses
- Cafe automation
- WhatsApp business assistant
- Small business workflow automation

---

# Key Highlights

- Real-time AI customer interaction
- Automated order processing
- AI-powered menu assistant
- Dynamic inventory management
- Smart conversational memory
- Scalable no-code automation system

---

# Screenshots

## Workflow Preview

![image alt]

## Chatbot Demo

```md
![WhatsApp Demo](./screenshots/demo.png)
```

---

# Demo Video

```md
[Watch Demo Video](YOUR_VIDEO_LINK_HERE)
```

---

# Future Improvements

- Payment gateway integration
- Voice message support
- Multi-language support
- Admin dashboard
- Customer analytics
- Delivery tracking system

---

# Repository Structure

```txt
project/
│
├── screenshots/
├── workflow/
├── README.md
└── demo-video/
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

## Setup

1. Import workflow into n8n
2. Configure WhatsApp Cloud API
3. Add Gemini API key
4. Connect Google Sheets
5. Activate workflow

---

# Author

## Tapabrata Maity

AI Automation Developer | n8n Workflow Builder | AI Chatbot Developer

GitHub: https://github.com/tapabrata07

---

# License

This project is for educational and portfolio purposes.
