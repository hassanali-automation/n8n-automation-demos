# n8n AI Automation Workflows

Ready-to-import n8n workflows that use Google Gemini AI with Gmail and Google Sheets.

| Workflow | What it does | Files |
|---|---|---|
| AI Email Follow-Up | New lead in Google Sheets, Gemini writes a follow-up email, Gmail sends it and checks for a reply | `ai-email-follow-up.json`, `README-ai-email-follow-up.md` |
| CV Screening AI | CV (PDF) arrives in Gmail, Gemini compares it with the job description, shortlist or reject, result saved to Sheets | `cv-screening-ai.json`, `README-cv-screening.md` |

## How to use
1. In n8n: Workflows > Import from file > choose the JSON file.
2. Connect your own Gmail, Google Sheets and Gemini credentials.
3. Test with sample data first.

All workflows are cleaned: no API keys, credentials or personal data.

Built by [Hassan Ali](https://github.com/hassanali-automation) · AI Automation Specialist
