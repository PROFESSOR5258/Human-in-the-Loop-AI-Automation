# Human-in-the-Loop AI Sales & Decision Automation

## 🚀 Overview
This project demonstrates a **human-in-the-loop AI automation system** built with **n8n**, designed for scenarios where AI-generated decisions **must be reviewed and approved by humans** before execution.

It reflects **enterprise-grade AI governance**, not blind automation.

---

## 🎯 Key Features
- AI-generated sales & response emails
- Human approval via Gmail (Send & Wait)
- Feedback classification (Approved / Declined)
- Automatic AI revision loop
- CRM-triggered automation (Airtable)
- Structured output validation
- Full audit-friendly workflow

---

## 🧠 How It Works
1. New lead enters Airtable CRM
2. AI Sales Agent drafts a response email
3. Email is sent to a human reviewer
4. Reviewer approves or requests changes
5. If declined → AI revises the content
6. Once approved → final email is sent to the lead

---

## 🛠 Tech Stack
- n8n
- OpenAI GPT-4 / GPT-4.1-mini
- Google Gemini (classification)
- Airtable API
- Gmail API
- LangChain Agents

---

## 💼 Use Cases
- AI-assisted sales outreach
- Client onboarding workflows
- Recruitment communication
- Compliance-sensitive AI systems
- Enterprise decision pipelines

---

## 🧠 Why Human-in-the-Loop Matters
- Prevents AI hallucination risks
- Enables compliance & accountability
- Builds trust in AI-driven systems
- Aligns with real enterprise workflows

---

## 📈 Business Impact
- Faster response times without losing control
- Consistent communication quality
- Reduced manual effort with safety checks

---

## 📌 Status
Enterprise-ready • Audit-friendly • Production-grade
