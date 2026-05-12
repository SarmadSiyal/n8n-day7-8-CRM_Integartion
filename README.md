# CRM Automation System using n8n

## Overview

This project is a complete CRM Automation System built using n8n, Google Sheets, Gmail, Slack, and Webhooks.

The system automates:

- Lead capture
- Duplicate lead detection
- CRM management
- Activity tracking
- Follow-up reminders
- Email notifications
- Slack notifications

The project was built as part of the Day 7–8 CRM Integration & Tracking Automation task.

---

# Features

## Lead Capture Automation
- Capture leads from HTML form
- Store leads in Google Sheets CRM
- Prevent duplicate lead creation
- Update existing leads automatically
- Send professional confirmation emails
- Notify internal team using Slack

---

## CRM Lead Management
- Admin CRM update form
- Lead status management
- Activity tracking
- Follow-up scheduling
- CRM update notifications
- Lead existence validation

---

## Automated Follow-Up Tracking
- Daily automated follow-up checks
- Detect overdue leads
- Notify internal team automatically
- Improve CRM follow-up management

---

# Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Google Sheets | CRM database |
| Gmail | Email notifications |
| Slack | Internal notifications |
| HTML/CSS/JavaScript | Frontend forms |
| Webhooks | Form communication |

---

# Repository Structure

```bash
crm-automation-system/
│
├── workflows/
│   ├── 01-lead-capture-duplicate-management.json
│   ├── 02-crm-management-activity-tracking.json
│   └── 03-followup-reminder-system.json
│
├── assets/
│   ├── workflow-1-lead-capture.png
│   ├── workflow-2-crm-management.png
│   ├── workflow-3-followup-reminder.png
│   ├── google-sheets-crm.png
│   ├── gmail-notification.png
│   ├── slack-notification.png
│   ├── admin-form.png
│   └── lead-form.png
│
├── forms/
│   ├── lead-capture-form.html
│   └── admin-crm-update-form.html
│
├── documentation/
│   └── premium-crm-automation-documentation.md
│
├── README.md
│
└── .gitignore
