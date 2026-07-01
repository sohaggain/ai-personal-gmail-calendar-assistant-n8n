# AI Personal Gmail & Calendar Assistant

An AI-powered Personal Assistant built using n8n, OpenAI GPT-5, Gmail, Google Calendar, Google Contacts, and Telegram.

This assistant helps automate email management, calendar scheduling, contact lookup, and productivity tasks through a single conversational interface.

---

## Features

### Email Management
- Send emails
- Reply to emails
- Search emails
- Delete emails
- Apply labels to emails
- Manage Gmail inbox using natural language

### Contact Lookup
- Search Google Contacts
- Find recipient emails automatically
- Smart contact matching

### Calendar Management
- Create events
- Update events
- Reschedule meetings
- Cancel events
- Check availability
- Manage schedules through chat

### Voice Commands
- Receive voice messages from Telegram
- Convert speech to text using OpenAI Whisper
- Execute email and calendar actions from voice instructions

### AI Agent Capabilities
- GPT-5 powered AI agent
- Multi-agent architecture
- Tool calling
- Context memory
- Natural language interaction

---

## Tech Stack

### AI
- OpenAI GPT-5
- OpenAI Whisper

### Automation
- n8n

### Communication
- Telegram Bot API

### Google Services
- Gmail API
- Google Calendar API
- Google Contacts API

### Memory
- n8n Memory Buffer

---

## Workflow Architecture

Telegram User
↓
Telegram Trigger
↓
Voice/Text Detection
↓
Voice Transcription (Whisper)
↓
AI Agent (GPT-5)
↓
├── Gmail Agent
│   ├── Send Email
│   ├── Reply Email
│   ├── Delete Email
│   ├── Label Email
│   └── Search Email
│
└── Calendar Agent
    ├── Create Event
    ├── Update Event
    ├── Delete Event
    └── Check Availability
↓
Telegram Response

---

## Example Commands

### Email Commands

Send an email to John about tomorrow's meeting.

Reply to the latest email from Sarah and thank her.

Delete the email from Amazon received today.

Label all client emails as Important.

Show me unread emails from this week.

### Calendar Commands

Schedule a meeting tomorrow at 10 AM.

Move my client meeting to Friday.

Cancel today's appointment.

What meetings do I have this week?

### Voice Commands

Users can send voice messages through Telegram and the assistant will automatically:

1. Transcribe the audio
2. Understand the intent
3. Execute the requested action
4. Return a response

---

## Security Features

- OAuth authentication
- Gmail permission controls
- Calendar access controls
- Contact lookup validation
- Tool-based action verification
- Action confirmation before completion

---

## Business Use Cases

### Entrepreneurs
- Inbox management
- Meeting scheduling
- Contact organization

### Freelancers
- Client communication
- Follow-ups
- Appointment management

### Agencies
- Team scheduling
- Lead communication
- Workflow automation

### Business Owners
- Productivity automation
- Email processing
- Calendar management

---

## Results

✅ Reduced manual email management

✅ Faster scheduling and coordination

✅ Unified communication interface

✅ Voice-powered productivity

✅ AI-driven workflow automation

---

## Future Improvements

- Multi-user support
- CRM integration
- Slack integration
- WhatsApp integration
- AI meeting summaries
- Automated follow-up sequences
- Advanced email classification

---

## Author

### Sohag Gain

Founder — AI Smart Galaxy

AI Automation Specialist | n8n Expert | AI Agent Developer

### Connect

Website: https://www.aismartgalaxy.com

LinkedIn: www.linkedin.com/in/sohag-gain

---

## License

MIT License
