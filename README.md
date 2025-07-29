# Lexi - AI Chatbot using n8n + Google Gemini + LangChain

This project is a workflow designed in [n8n](https://n8n.io/) that implements an AI-powered chatbot called **Lexi**.

## Features
- Triggered on receiving chat messages
- Powered by Google Gemini API (via LangChain)
- Uses Memory Buffer to retain conversation context
- Built entirely using n8n's visual workflow designer

## Files
- `Lexi.json`: Exported n8n workflow file

## Usage
1. Import `Lexi.json` into your local or hosted n8n instance.
2. Setup credentials for Google Gemini (PaLM API).
3. Activate the workflow and start chatting!

## How to Import into n8n
- Go to n8n
- Click the top-right menu > **Import workflow**
- Upload `Lexi.json`

---

*Project created and managed by Pujitha K.*
