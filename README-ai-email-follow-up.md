# AI Email Follow-Up Automation (n8n)

**Portfolio demo built and tested in n8n.**

## Problem
New leads wait too long for a reply, or follow-ups are forgotten.

## What it does
1. A new row is added to a Google Sheet (new lead).
2. A Gemini-powered AI agent writes a short follow-up email.
3. Gmail sends the email to the lead.
4. The workflow waits, then checks Gmail for a reply.

## Tools
n8n, Google Sheets, Gmail, Google Gemini.

## Setup
1. Import `ai-email-follow-up.json` in n8n (Workflows > Import from file).
2. Connect your own Google Sheets, Gmail and Gemini credentials.
3. Select your own Google Sheet (needs columns such as Name, Email, Message).
4. Test with sample data only.

No credentials, keys or personal data are included in this repository.
