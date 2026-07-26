# 🛡️ ScamShield

### AI-Powered Explainable Fraud Prevention Assistant using NitroStack MCP

ScamShield is an AI-powered fraud prevention system designed to help users identify suspicious WhatsApp messages, phishing links, OTP scams, fake bank messages, and other social-engineering attacks.

The project uses **NitroStack MCP**, **Gemini AI**, and **Twilio WhatsApp** to analyse suspicious messages and provide an explainable risk assessment.

---

## 🎯 Problem Statement

Online fraudsters frequently use fake bank messages, phishing links, OTP requests, urgency, and impersonation to trick users into revealing sensitive information.

Many users may not be able to determine whether a message is genuine or fraudulent.

ScamShield provides an intelligent security assistant that analyses suspicious messages before users take potentially dangerous actions.

---

## ✨ Features

- 🔍 Message scam analysis
- 🔐 OTP and credential protection
- 🔗 Suspicious link analysis
- 📞 Phone number risk analysis
- 🏦 Bank impersonation detection
- 🧠 AI-powered contextual fraud analysis
- 📊 Explainable risk assessment
- 💬 WhatsApp integration
- ⚙️ NitroStack MCP security tools

---

## 🛠️ NitroStack MCP Tools

ScamShield contains specialised MCP tools:

- `otp_share_guard` – Detects attempts to obtain OTPs or sensitive credentials
- `analyze_message_intent` – Analyses suspicious message intent
- `check_link_safety` – Checks suspicious URLs
- `phone_number_risk_check` – Analyses potentially suspicious phone numbers
- `verify_bank_identity` – Helps identify bank impersonation attempts

---

## 🤖 AI Integration

Gemini AI is used for contextual analysis of suspicious messages.

The AI examines indicators such as:

- Urgency
- Threats
- Requests for credentials
- OTP requests
- Bank impersonation
- Suspicious links
- Social-engineering language

The AI analysis works together with ScamShield's specialised MCP security tools to generate an explainable fraud-risk assessment.

---

## 🏗️ Architecture

User  
↓  
WhatsApp  
↓  
Twilio  
↓  
ScamShield Webhook  
↓  
NitroStack MCP Server  
↓  
ScamShield Security Tools  
↓  
Gemini AI Analysis  
↓  
Risk Assessment  
↓  
Safety Recommendation  
↓  
WhatsApp User

---

## 💻 Technology Stack

- TypeScript
- Node.js
- NitroStack
- Model Context Protocol (MCP)
- Gemini AI
- Twilio WhatsApp API
- ngrok
- GitHub

---

## 🚀 Local Development

Install dependencies:

```bash
npm install