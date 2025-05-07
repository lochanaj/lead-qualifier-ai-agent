# Lead Qualifier & Notifier AI Agent

## Overview
This project automates the lead qualification process by integrating a custom web scraper tool built with Relevance AI into an n8n workflow. The agent scrapes company websites from inbound lead submissions, evaluates leads based on predefined qualification criteria, and automates next steps including lead categorization and email notifications. Unqualified leads receive automated responses offering alternative support, streamlining lead management and improving response efficiency.

## Features
- **Custom Web Scraper:** Extracts relevant company data from lead-submitted URLs using a Relevance AI scraper tool.
- **Lead Qualification:** Evaluates leads against customizable criteria to determine qualification status.
- **Lead Categorization:** Classifies qualified leads (e.g., SaaS or Agency) to route them to the appropriate sales representatives.
- **Automated Notifications:** Sends email notifications with summaries to sales reps for qualified leads.
- **Responsive Follow-up:** Automatically responds to unqualified leads with alternative options to maintain engagement.
- **Workflow Automation:** Entire process orchestrated using n8n, enabling seamless automation without manual intervention.

## Tech Stack
- **Relevance AI:** Custom web scraper for data extraction.
- **n8n:** Workflow automation platform to build and manage the lead qualification logic and notifications.
- **Email Automation:** Integrated within n8n for sending notifications and responses.

## How It Works
1. Lead submits a form with their company website URL.
2. The Relevance AI scraper extracts key information from the website.
3. The AI agent evaluates the lead based on qualification criteria defined in the workflow.
4. If qualified:
   - The lead is categorized (e.g., SaaS or Agency).
   - An email notification with a summary is sent to the appropriate sales rep.
5. If not qualified:
   - An automated response is sent to the lead offering alternative support options.
