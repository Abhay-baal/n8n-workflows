# Push Notification Agent

This n8n workflow sends a push notification to my mobile whenever a task or workflow finishes successfully. It's a simple way to know when an automation has completed without checking n8n manually.

## Workflow

```text
Task Completed
      ↓
Send Push Notification
      ↓
Mobile Device
```

## Requirements

* Push notification service credentials
* n8n
