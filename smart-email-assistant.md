# Email Automation with Zapier

## Overview
This project automates personalized client emails using no-code tools. It helps streamline communication by sending tailored emails based on meeting and client data logged in Google Sheets.

#Problem
Every client interaction has a similar workflow with similar emails being sent. The small differences are client interests and followups. So with this agent, when we add new rows with tailored comments, an email will be sent to the client. 


## Tools Used
- **Zapier** — Automation platform to connect apps and automate workflows  
- **Google Sheets** — Acts as the data source and trigger for new client info  
- **Gmail** — Sends personalized emails based on templates and data  
- **Formatter by Zapier** — Replaces placeholders with actual client data dynamically

## How It Works
1. A new row is added to the Google Sheet with client meeting details.  
2. Zapier triggers and runs formatter steps to replace placeholders in an email template (e.g., `{{ClientName}}`, `{{MeetingDate}}`).  
3. Gmail sends a personalized email to the client automatically.

## How to Use
- Add meeting details or client info to the Google Sheet.  
- Ensure Zapier is active and connected to your Gmail.  
- The email is sent automatically without manual intervention.

## Benefits
- Saves time by automating repetitive email tasks  
- Ensures consistent, personalized client communication  
- No coding required — fully no-code solution

## Links
- [Zapier](https://zapier.com)  
- [Google Sheets](https://sheets.google.com)  
- [Gmail](https://mail.google.com)  
