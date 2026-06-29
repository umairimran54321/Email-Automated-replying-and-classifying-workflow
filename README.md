# Email-Automated-replying-and-classifying-workflow
📌 Project Overview

This project automates the process of receiving, classifying, and responding to emails using n8n.

The workflow analyzes incoming emails, determines whether they are Order Emails or Inquiry Emails, and sends an appropriate automated response based on the classification.

🚀 Features
Automatically receives incoming emails.
Classifies emails into:
📦 Order Emails
❓ Inquiry Emails
Sends different automated replies based on the email type.
Reduces manual email handling.
Demonstrates workflow automation using conditional logic.
🛠️ Tools Used
n8n
Email Trigger
Text Classifier
IF Node
Gmail/SMTP
AI Model (for email classification)
📋 Workflow Steps
Receive a new email.
Extract the email subject and body.
Classify the email as either:
Order
Inquiry
Route the email based on the classification.
Generate the appropriate response.
Send the automated reply to the sender.
📂 Workflow Logic

Email Received
↓
Extract Email Content
↓
Text Classifier
↓
┌───────────────┐
│ │
Order Inquiry
│ │
Generate Generate
Order Reply Inquiry Reply
│ │
└──────┬────────┘
↓
Send Response

💡 Learning Outcomes
Workflow automation with n8n
AI-powered email classification
Conditional branching using IF nodes
Automated email responses
Practical business process automation
Nodes:
Gmail trigger
Input(2).jpeg
Ai Agent
Input(3).jpeg
If
Input(4).jpeg
Open Ai "order"
Input (5).jpeg
Open Ai "inquiry"
Input(6).jpeg
Merge
Input(7).jpeg
Gmail draft

My workflow.json
