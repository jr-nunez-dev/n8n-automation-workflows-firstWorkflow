# Hello World — My First n8n Workflow 🚀

Every journey has a beginning.

This repository contains the **very first workflow** I built while taking my first steps into n8n through an introductory quiz. Although the workflow itself is simple, it represents the project that introduced me to workflow automation and ultimately led me to pursue automation engineering more seriously.

---

## About

This repository is preserved as a milestone in my learning journey.

The workflow demonstrates a straightforward ETL-style automation that:

1. Retrieves issues from Jira.
2. Selects the required fields.
3. Converts the data into an Excel spreadsheet.
4. Uploads the generated report to Google Drive.

While basic compared to the projects I've built since, it taught me the core concepts that every future workflow would build upon.

---

## Workflow Overview

```text
Manual Trigger
      │
      ▼
Retrieve Jira Issues
      │
      ▼
Transform Data
      │
      ▼
Generate Excel File
      │
      ▼
Upload to Google Drive
```

The workflow uses a manual trigger, queries Jira issues with a predefined JQL filter, selects only the required fields, converts the results into an Excel file, and uploads the generated report to Google Drive. :contentReference[oaicite:0]{index=0}

---

## What I Learned

Although simple, this project introduced me to many concepts that became fundamental in my automation journey:

- Workflow execution
- Application integrations
- Data transformation
- ETL concepts
- File generation
- Cloud storage automation
- Workflow sequencing
- Automation thinking

---

## Looking Back

Today, I build significantly more advanced workflows involving:

- AI Agents
- Multi-agent orchestration
- Enterprise integrations
- Production-inspired automations
- Business process automation
- Intelligent workflow design

This repository is a reminder that every complex automation starts with a simple first workflow.

---

## Why I Keep This Repository

I intentionally keep this project as a personal milestone.

It's a reminder of where I started, how much I've learned, and how every new technology begins with a single workflow.

No matter how large my automation portfolio becomes, this will always be **Workflow #1**.
