# 🤖 AI Email Classifier

An AI-powered email classification workflow built with n8n.

---

## Features

- Monitors incoming Gmail messages
- Extracts email content
- Uses AI to classify emails
- Categorizes emails automatically
- Reduces manual email sorting

---

## Technologies

- n8n
- Gmail
- Groq API
- Llama 3
- JavaScript

---

## Workflow

Gmail Trigger
→ Extract Email
→ AI Classification
→ Parse AI Response
→ Output Result

---

## Workflow Screenshot

![Workflow](screenshots/Workflow.png)

---

## Gmail Trigger

Monitors incoming emails.

![Gmail Trigger](screenshots/Gmail-Trigger.png)

---

## AI Classification

Uses Groq Llama to classify the email.

![AI Classification](screenshots/AI-Classification.png)

---

## Parse AI Response

Extracts the structured AI response.

![Parse AI Response](screenshots/Parse-AI-Response.png)

---

## Classification Result

Example of the classified email output.

![Classification Result](screenshots/Classification-Result.png)
