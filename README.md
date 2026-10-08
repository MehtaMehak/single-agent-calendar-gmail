# Single-Agent Calendar & Gmail Assistant

This is my first AI Agent workflow built using **n8n**.

The agent checks my Google Calendar for the day, finds the **two most important events**, explains why they are important, and sends the summary to my Gmail.

### Workflow

```text
Schedule Trigger
       ↓
    AI Agent
    ↙      ↘
Google     Gmail
Calendar
```

### Tools Used

* n8n
* Groq
* Google Calendar
* Gmail API

### What I Learned

This project helped me understand how an **AI Agent uses tools and makes decisions** instead of just generating text.

**Next step:** Learning MCP and how it is different from directly connecting tools.

### Note

The workflow file in this repository uses placeholder values for personal information and does not include API keys or credentials.
