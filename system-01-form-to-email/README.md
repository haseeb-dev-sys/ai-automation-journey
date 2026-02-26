# System 01: Form → Sheet → Email

## What It Does

1. User submits Google Form
2. Response auto-saves to Google Sheet
3. n8n detects new row
4. Email notification sent immediately

## Tools Used

| Tool | Purpose | Cost |
|------|---------|------|
| Google Forms | Data collection | Free |
| Google Sheets | Data storage | Free |
| n8n Cloud | Workflow automation | Free tier |
| Gmail | Email delivery | Free |

## Build Time

- Total: 2 hours
- Errors encountered: 3
- Final working version: Hour 2

## Errors & Fixes

| Error | Cause | Fix |
|-------|-------|-----|
| Webhook not triggering | Google Forms webhook unreliable | Switched to Google Sheets trigger (polling) |

## Screenshot

![Workflow](workflow-screenshot.png)

## Test Data

See [test-data.json](test-data.json) for sample submission.
