# CV Screening AI Workflow (n8n)

**Portfolio demo built in n8n. Tested with sample CVs.**

## Problem
Reading every CV for a first screening takes time.

## What it does
1. A new email with a CV (PDF) arrives in Gmail.
2. The PDF text is extracted.
3. A Gemini AI agent compares it with a job description.
4. An IF node splits shortlist and reject.
5. An email is sent and the result is saved in Google Sheets.

A human should always make the final hiring decision.

## Tools
n8n, Gmail, Google Sheets, Google Gemini.

## Setup
1. Import `cv-screening-ai.json` in n8n.
2. Connect your own Gmail, Sheets and Gemini credentials.
3. Select your own Google Sheet.
4. Edit the job description inside the AI Agent node.

No credentials, keys or personal data are included in this repository.
