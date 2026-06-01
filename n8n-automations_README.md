# n8n Automations

A collection of workflow automations built in [n8n](https://n8n.io/) — including an event-triggered data alert pipeline and an AI chatbot.

## 1. Telegram Data-Alert Automation

Automatically sends the latest analysis data to Telegram whenever a source Excel/data file is updated — giving the team instant updates with no manual sharing.

**Flow:**
- Detects when the data/Excel file is updated (trigger).
- Reads the latest analysis data.
- Formats and sends it to a Telegram chat/channel automatically.

**Why it matters:** Removes the manual step of exporting and forwarding updated numbers. The team is notified the moment data changes.

## 2. AI Chatbot

A conversational chatbot workflow that integrates messaging with LLM/API calls to answer queries and trigger actions automatically.

**Flow:**
- Receives an incoming message.
- Passes it to an LLM / API.
- Returns a response and can trigger downstream actions.

## Tech Stack

- **Platform:** n8n (workflow automation)
- **Integrations:** Telegram API, LLM / HTTP APIs, webhooks

## Notes

This repo documents the workflow designs. Exported workflow JSON can be added here so others can import the flows directly into their own n8n instance.

## About

Built by **Christian Cesar Baclayo** — Automation & Python Developer.
Portfolio: https://jinzoa2014.github.io/chan/ · Email: christiancpb123@gmail.com
