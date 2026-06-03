# Real Estate Investment Automation System

> AI-powered investment research pipeline that matches properties, runs financial analysis, generates reports, and notifies the team automatically using n8n, OpenAI, Google Sheets, Slack, and Gmail.

**Industry:** Real Estate
**Built for:** Investment firms and real estate teams that want to automate property research and deal reporting without losing hours to manual data gathering.

---

## Demo

[Watch the full walkthrough →](https://drive.google.com/file/d/11TgDuEtlnMu0DBSbk_kovLGjmxuKo37l/view)

<img width="852" height="405" alt="Github real" src="https://github.com/user-attachments/assets/8e1a53ce-9f65-44c7-98ac-a21aab8f1459" />


---

## The Problem

A client comes in looking for a property investment opportunity. The team has to start from scratch every time.

Searching through listings. Calling agents. Comparing multiple opportunities. Checking locations and pricing. Running ROI and cash flow calculations. Trying to organize everything into spreadsheets and reports before management can even review the deal.

When multiple requests come in at the same time, the entire process breaks down. Things get missed. Deals get delayed. Hours disappear into manual data gathering that should not require human attention.

---

## The Solution

A fully automated investment research and reporting pipeline built inside n8n. The moment a client submits their investment requirements, the system takes over.

It matches properties based on the client's criteria, pulls live listing data, runs financial analysis, generates a formatted investment report, updates the CRM, and sends instant notifications to the team on Slack and a report to the client via Gmail. All without anyone touching a spreadsheet.

---

## How It Works

1. **Client submits investment requirements via intake form** — The workflow triggers the moment a client fills out the intake form. Name, budget, target location, property type, and investment goals are captured automatically and passed into the pipeline.
2. **AI Agent matches and researches properties** — An n8n AI Agent powered by OpenAI processes the client's criteria and queries property listing APIs to find matching opportunities. It filters by location, price range, property type, and availability.
3. **Financial analysis runs automatically** — For each matched property, the system calculates ROI, projected cash flow, yield estimates, and key financial metrics. No manual spreadsheet work required.
4. **Investment report is generated** — A structured report is compiled for the matched properties, including all property details, listing links, agent contacts, and financial projections. Ready for management review.
5. **CRM is updated** — All deal data, client requirements, matched properties, and generated reports are pushed into the Google Sheets CRM. Every request has a clean audit trail.
6. **Team is notified on Slack** — An instant Slack notification goes to the relevant team channel with a summary of matched properties and a link to the full report.
7. **Report delivered via Gmail** — A formatted report email is sent automatically to the client or internal distribution list.

---

## Tech Stack

| Tool | Role |
|---|---|
| **n8n** | Core workflow engine and orchestration layer |
| **n8n AI Agent Node** | Runs the LangChain-based agent logic for property matching and criteria processing |
| **OpenAI API** | Powers the agent's natural language understanding and decision making |
| **REST APIs** | Pulls live property listing data and external data sources |
| **Google Sheets** | CRM that stores client requests, matched properties, and generated reports |
| **Slack** | Real-time team notifications with deal summaries |
| **Gmail** | Automated report delivery to clients and internal teams |

---

## Results

- Eliminated hours of manual research per client request
- Zero deals missed due to manual process gaps
- Team shifted focus from data gathering to deal review and closing
- All client requests centralized in one trackable, searchable system
- System runs 24/7 without supervision

---

## About

Built by **Charles Emmanuel** — AI & Automation Systems Engineer.
Lagos, Nigeria | [LinkedIn](https://linkedin.com/in/charles-emmanuel-automation) | charlestaylurr@gmail.com

I build systems that remove repetitive manual work so teams can focus on what actually matters. If your business is losing time or money to broken processes, reach out.
