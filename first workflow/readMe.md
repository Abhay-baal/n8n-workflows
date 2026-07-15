# 📈 Stock Portfolio Updater

This n8n workflow reads my stock portfolio from a Google Sheet, gets the latest stock prices using the Marketstack API, updates the sheet with the new prices, and sends a push notification once everything is completed successfully.

## Workflow

```text
Chat Trigger
    ↓
Google Sheets (Portfolio)
    ↓
Marketstack API
    ↓
Update Google Sheets
    ↓
Push Notification
```

## Requirements

* Google Sheets
* Marketstack API Key
* Push Notification credentials
