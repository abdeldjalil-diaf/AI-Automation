# AI & Automation Portfolio

This repository showcases AI-powered automation systems built using n8n, large language models (LLMs), and API integrations.

The projects demonstrate workflow orchestration, document processing, AI-based text analysis, and structured data extraction.

---

## 🚀 About This Repository

The goal of this portfolio is to demonstrate practical skills in:

- Automation engineering
- AI integration in real-world workflows
- REST API usage
- Email and document processing
- Structured data generation
- Backend logic design
- System architecture thinking

All workflows are built using n8n and integrated with external AI models and APIs.

---

## 🛠 Technologies Used

- n8n (Workflow Automation)
- REST APIs
- Gmail API
- Telegram Bot API
- PDF Text Extraction
- LLM Chains
- OpenRouter / Google Gemini
- Structured Output Parsing
- JSON Data Processing
- Git & GitHub

---

# 📂 Projects

---

## 1️⃣ AI Chatbot with Memory (Gemini)

An AI-powered chatbot that maintains contextual memory across interactions.

### 🔹 Features

- Chat trigger-based workflow
- AI Agent integration
- Google Gemini model
- Session-based memory
- Context-aware responses

### 🔹 Architecture

User → Chat Trigger → AI Agent → Gemini Model → Response

### 🔹 Use Case

Demonstrates conversational AI integration inside an automated workflow system.

---

## 2️⃣ Telegram Automation Bot

An automated messaging system integrating Telegram with APIs and AI processing.

### 🔹 Features

- Telegram message trigger
- Scheduled automation
- External API requests
- Automated formatted responses
- Optional AI-generated replies

### 🔹 Workflow Process

1. Telegram trigger or scheduled trigger
2. HTTP request to external API
3. Data processing
4. Send response back to Telegram

### 🔹 Architecture

Telegram → n8n Trigger → API Request → Processing → Telegram Response

### 🔹 Use Case

Shows real-time messaging automation and API integration inside a workflow system.

---

## 3️⃣ AI CV Parser from Gmail

An intelligent automation system that extracts structured information from CVs received via Gmail.

### 🔹 Workflow Process

1. Gmail Trigger detects a new email
2. Extract PDF attachment
3. Extract raw text from CV
4. Send text to LLM for analysis
5. Generate structured JSON output

### 🔹 Extracted Information

- Full Name
- Email Address
- Phone Number
- Skills
- Education
- Work Experience

### 🔹 Architecture

Gmail → Extract PDF → Text Processing → LLM Analysis → Structured Data Output

### 🔹 Example Output

```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "phone": "+39 123 456 789",
  "skills": ["Python", "Machine Learning", "Data Analysis"],
  "education": "Master in Computer Science",
  "experience": "2 years as Data Analyst"
}
