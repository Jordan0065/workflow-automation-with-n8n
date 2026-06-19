# AI Customer Support Chatbot with Product Catalog Lookup (n8n)

This project is an **AI-powered customer support chatbot** built using **n8n**, **OpenAI GPT‑5 Mini**, and **Google Sheets**.  
It allows customers to ask natural-language questions about products, pricing, SKUs, and availability — and receive instant, accurate responses based on a live product catalog stored in Google Sheets.

The workflow also includes an optional **inventory monitoring system** that detects out-of-stock products mentioned in AI responses and automatically sends email alerts to inventory managers.

---

# Features

- AI-powered customer support assistant  
- Real-time product lookup via Google Sheets  
- Natural language conversations using GPT‑5 Mini  
- Automated customer responses  
- SKU, price, and availability retrieval  
- Optional out-of-stock detection  
- Automated Gmail notifications  
- Fully customizable no-code workflow in n8n  

---

# Workflow Architecture

```text
Customer Message
       │
       ▼
Chat Trigger
       │
       ▼
AI Agent
       │
 ┌─────┴─────┐
 ▼           ▼
Chat      Stock Analysis Agent (Optional)
                 │
                 ▼
                IF
                 │
                 ▼
            Gmail Alert







