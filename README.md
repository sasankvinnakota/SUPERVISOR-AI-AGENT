Supervisor AI Agent

A Telegram-integrated AI workflow built in n8n that receives user requests, understands intent, chooses the correct tool, performs the task, and sends the final response back to Telegram.

Workflow Flow

Telegram Trigger receives the incoming message

TAKE MESSAGE HERE extracts the text

Supervisor AI Agent reads and understands the request

The agent checks Google Sheets contacts first

The agent decides whether to:

send an email

schedule a meeting

do research

handle a default case

The appropriate tool is executed

The final result is sent back through Telegram

Node-by-Node Explanation
1. Telegram Trigger

Starts the workflow when a message is received on Telegram.

2. TAKE MESSAGE HERE

Extracts the incoming Telegram message text into a cleaner field for processing.

3. Supervisor AI Agent

Acts as the main brain of the workflow. It analyzes the user request and decides which action to perform.

4. Window Buffer Memory

Stores recent conversation context so the agent can handle follow-up messages more intelligently.

5. Google Gemini Chat Model

Provides the AI reasoning and decision-making capability for the Supervisor Agent.

6. Google Sheets Tool

Looks up saved contact details such as name, email, phone number, or company.

7. Gmail Tool

Sends emails when the user requests email-based actions.

8. Google Calendar Tool

Creates calendar events and schedules meetings based on user instructions.

9. Research Agent

Handles research and informational queries by generating clear answers.

10. Telegram

Sends the final response, summary, or confirmation message back to the Telegram chat.

What This Workflow Achieves

This workflow creates a personal AI operations assistant on Telegram that can:

understand natural language

search saved contacts

send emails automatically

schedule meetings

answer general questions

respond instantly on Telegram

Features

Telegram-based interaction

AI-powered decision making

Google Sheets contact lookup

Automated Gmail sending

Google Calendar scheduling

Research question handling

Conversation memory support

Use Cases

Contact lookup from a stored database

Sending appointment or business emails

Scheduling meetings with attendees

Answering research or informational questions

Automating Telegram-based assistant tasks

Tools Used

n8n

Telegram Trigger

Google Gemini Chat Model

Google Sheets

Gmail

Google Calendar

AI Agent / Research Agent

Window Buffer Memory

Summary

The Supervisor AI Agent is a smart Telegram assistant workflow in n8n that automates communication, scheduling, contact lookup, and research tasks by using AI with connected tools like Google Sheets, Gmail, Google Calendar, and Telegram.
