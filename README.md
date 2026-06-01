# 🏋️ Gym Management Automation Suite (n8n + Airtable)

A comprehensive automation system designed to manage the full lifecycle of gym memberships—from registration and expiry monitoring to renewal auditing. 

## 📂 Projects
This repository contains three interconnected workflows:

### 1. 📝 User Registration (`project-1-registration/`)
- **Goal:** Automate new member onboarding.
- **Features:** Webhook ingestion, duplicate checking, Airtable creation, and dual email notifications (User + Admin).
- **[View Project 1 Details →](<img width="1497" height="684" alt="workflow-preview png" src="https://github.com/user-attachments/assets/a99aba3d-10ff-43b2-8244-fbb875210773" />
)**

### 2. ⏰ Expiry Notifications (`project-2-expiry-notifications/`)
- **Goal:** Reduce churn through automated monitoring.
- **Features:** Scheduled 7-day and 30-day warnings, auto-updating expired statuses, and daily summary reports.
- **[View Project 2 Details →](project-2-expiry-notifications/README.md)**

### 3. 🔄 Renewal & Audit System (`project-3-renewal-audit/`)
- **Goal:** Handle renewals with strict data integrity.
- **Features:** "Snapshot" audit technique, dynamic date math, history logging, and idempotent webhook responses.
- **[View Project 3 Details →](project-3-renewal-audit/README.md)**

## 🛠️ Tech Stack
- **Orchestration:** n8n (Workflow Automation)
- **Database:** Airtable (Relational Data & Audit Logs)
- **Communication:** Gmail / SMTP & Webhooks
- **Testing:** Postman & cURL

## 📸 Visuals
*(Drag and drop your screenshots here so people can see the workflow logic immediately)*
![Workflow Preview](assets/workflow-preview.png)

## 🚀 Quick Start
1. Download any `*-workflow.json` file.
2. Import into n8n via **Menu → Import from File**.
3. Configure your Airtable & Gmail credentials.
4. Follow the specific README in each project folder for setup details.

---
*Built by [Your Name] | Automated by n8n*
