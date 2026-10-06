# 📧 Gmail Email Automation using n8n

This project is a simple email automation workflow built using **n8n** and **Gmail**.

The workflow allows a user to trigger an automation manually and automatically send an email through Gmail.

## 🚀 Project Overview

This automation contains two main nodes:

1. **Manual Trigger**
   - Starts the workflow when the user clicks "Execute Workflow".

2. **Gmail - Send a Message**
   - Sends an email automatically using the connected Gmail account.

## 🔄 Workflow

Manual Trigger
      ↓
Gmail - Send a Message
      ↓
Email Sent

## 🛠️ Technologies Used

- n8n
- Gmail
- Google OAuth 2.0
- Workflow Automation

## ✨ Features

- Simple email automation
- Manual workflow execution
- Gmail integration
- No coding required
- Easy to customize
- Can be extended with additional automation steps

## ⚙️ How It Works

1. Open the n8n workflow.
2. Click **Execute Workflow**.
3. The Manual Trigger starts the workflow.
4. The Gmail node receives the data.
5. Gmail automatically sends the configured email.

## 🔐 Gmail Authentication

The Gmail node uses Google OAuth 2.0 authentication.

**Important:** Never upload or share OAuth credentials, access tokens, refresh tokens, API keys, passwords, or `.env` files containing secrets on GitHub.

## 📁 Project Structure

```text
gmail-n8n-automation/
│
├── workflow.json
└── README.md
