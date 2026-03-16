# SUPERVISOR-AI-AGENT

Workflow flow in order

Telegram Trigger receives message

TAKE MESSAGE HERE extracts text

Supervisor AI Agent reads request

Agent checks Google Sheets contacts first

Agent decides whether to:

send an email,

schedule a meeting,

do research,

or handle a default case

Proper tool is executed

Final result is sent back through Telegram

Node-by-Node Explanation

1. Telegram Trigger

Starts workflow when a Telegram message arrives.

2. TAKE MESSAGE HERE

Extracts the message text into a cleaner field.

3. Supervisor AI Agent

Main brain of the workflow. Decides what to do.

4. Window Buffer Memory

Keeps recent conversation context.

5. Google Gemini Chat Model

Provides AI reasoning for the supervisor.

6. Google Sheets Tool

Looks up contact details.

7. Gmail Tool

Sends emails.

8. Google Calendar Tool

Creates calendar events.

9. Research Agent

Handles research/information questions.

10. Telegram

Sends the final response back to the user.

What This Workflow Achieves

This workflow creates a personal AI operations assistant on Telegram that can:

understand natural language,

search saved contacts,

send emails automatically,

schedule meetings,

answer general questions,

and respond back instantly on Telegram.
