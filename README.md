# AI Productivity Manager

An AI-powered Telegram bot that acts as your personal productivity assistant —
manage your Gmail, Google Calendar, and Google Tasks all from a single
Telegram chat using natural language.

## Features

### Gmail
- Summarise received emails
- View your last 5 emails at a glance
- Reply to any email directly from Telegram
- Send new emails to anyone

### Google Calendar
- Add events on a specific date
- View upcoming events
- Update or delete existing events

### Google Tasks
- Create new tasks
- View all your tasks
- Update existing tasks
- Delete tasks

## How It Works

1. You send a message to the Telegram bot in natural language
2. The AI Agent (powered by Google Gemini) understands your intent
3. It performs the action on Gmail, Google Calendar, or Google Tasks
4. You get a response back — all within Telegram

## Tech Stack

- **n8n** — Workflow automation
- **Google Gemini** — AI language model
- **Telegram Bot API** — Chat interface
- **Gmail API** — Email management
- **Google Calendar API** — Event management
- **Google Tasks API** — Task management

## Setup

1. Import the `.json` file into your n8n instance
2. Set up credentials for:
   - Telegram Bot (create via @BotFather)
   - Google OAuth2 (Gmail, Calendar, Tasks)
   - Google Gemini API key
3. Activate the workflow
4. Start chatting with your bot on Telegram!

## Usage Examples

> "Summarise my last 5 emails"
> "Reply to John's email saying I'll be there by 3pm"
> "Add a meeting on 10th April at 2pm"
> "Create a task to submit assignment by Friday"
> "Delete the dentist appointment from my calendar"

## About

Built with n8n's visual workflow automation and powered by Google Gemini AI,
AI Productivity Manager brings together your entire productivity stack into
one simple Telegram conversation.
