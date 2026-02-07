Employee Onboarding Automation (n8n)
📌 Overview

This project implements an end-to-end Employee Onboarding Automation using n8n. The workflow automatically processes new employee details, stores records, and sends structured email notifications to HR, managers, and the employee—reducing manual effort and ensuring a smooth onboarding experience.

🚀 Features

Trigger via Google Form 

Store employee data in Google Sheets

Send HTML email notifications to HR & Manager

 welcome email to the employee

Clean, modular, and easy-to-extend workflow

Secure credential handling (no secrets in repo)

🧩 Workflow Architecture

Trigger – Google Form submission or Webhook

Data Processing – Validate & format employee details

Storage – Append data to Google Sheets

Notifications – Send email alerts (HR / Manager / Employee)

Optional Extensions – Slack/Teams alerts, document generation

🛠️ Tech Stack

n8n (Workflow Automation)

Google Forms (Data Capture)

Google Sheets (Data Storage)

Gmail

Google Sheets (Data Storage)

Gmail / SMTP (Email Notifications)
