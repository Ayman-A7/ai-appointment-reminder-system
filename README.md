# AI Appointment Reminder System with Voice AI

An AI-powered appointment reminder workflow built with **n8n**, **Google Calendar**, **Google Gemini**, **Airtable**, **Twilio**, and **Vapi**. This automation retrieves upcoming appointments, generates personalized reminder scripts using AI, logs all reminders in Airtable, and is designed to deliver reminders via SMS or AI voice calls.

---

## 🚀 Features

- 📅 Automatically checks upcoming appointments from Google Calendar
- 🤖 Generates personalized reminder scripts using Google Gemini
- 📋 Stores reminder details in Airtable
- 📞 Voice AI integration with Vapi
- 📱 SMS integration with Twilio
- 🔄 Processes multiple appointments automatically
- 📊 Updates reminder status in Airtable
- ⚡ Fully automated with a scheduled trigger

---

## 🛠️ Tech Stack

- n8n
- Google Calendar API
- Google Gemini
- Airtable
- Twilio
- Vapi AI
- REST APIs

---

## 📌 Workflow

```text
Schedule Trigger
        │
        ▼
Google Calendar
        │
        ▼
Loop Over Items
        │
        ▼
Google Gemini AI
(Generate Reminder Script)
        │
        ▼
Airtable
(Create Reminder Log)
        │
        ▼
Vapi HTTP Request
(Initiate AI Voice Call)
        │
        ▼
Airtable
(Update Call Status)
```

---

## 📂 Repository Structure

```
ai-appointment-reminder-system/
│
├── workflow.json
├── README.md
├── .gitignore
└── screenshots/
    ├── workflow.png
    ├── calendar.png
    ├── airtable.png
    ├── gemini-output.png
    ├── vapi.png
    ├── twilio.png
    └── execution.png
```

---

## ⚙️ How It Works

1. The workflow runs automatically on a schedule.
2. Google Calendar retrieves upcoming appointments.
3. Each appointment is processed individually.
4. Google Gemini generates a personalized reminder.
5. Reminder details are stored in Airtable.
6. A request is sent to Vapi to initiate an AI voice call.
7. Airtable is updated with the call status.

---

## 📸 Screenshots

### Workflow
`screenshots/workflow.png`

### Google Calendar
`screenshots/calendar.png`

### Airtable Database
`screenshots/airtable.png`

### Gemini AI Output
`screenshots/gemini-output.png`

### Vapi Integration
`screenshots/vapi.png`

### Twilio Configuration
`screenshots/twilio.png`

### Workflow Execution
`screenshots/execution.png`

---

## 💡 Business Use Cases

- Dental Clinics
- Medical Practices
- Salons & Spas
- Coaching Businesses
- Law Firms
- Real Estate Agencies
- Consulting Firms

---

## 🔧 Requirements

- n8n
- Google Calendar Account
- Google Gemini API Key
- Airtable Account
- Vapi Account
- Twilio Account (optional for telephony integration)

---

## 📈 Skills Demonstrated

- AI Workflow Automation
- Prompt Engineering
- Google Calendar Integration
- Airtable Database Automation
- REST API Integration
- HTTP Request Configuration
- Voice AI Integration
- Multi-step Workflow Design
- AI-generated Customer Communication
- Scheduling & Automation

---

## 🚀 Future Improvements

- Two-way AI conversations
- Automatic appointment rescheduling
- WhatsApp reminders
- Email fallback notifications
- Voice analytics dashboard
- Retry logic for failed calls
- CRM integrations (HubSpot, Salesforce)
- Multi-language voice support

---

## 📚 What I Learned

This project helped strengthen my skills in:

- Building end-to-end AI automation workflows
- Integrating multiple third-party APIs
- Working with HTTP Request nodes in n8n
- Voice AI orchestration using Vapi
- Managing structured data with Airtable
- Scheduling automated workflows
- Creating production-style business automations

---

## 👨‍💻 Author

**Ayman Amjad**

GitHub: https://github.com/Ayman-A7

---

⭐ If you found this project interesting, feel free to star the repository!
