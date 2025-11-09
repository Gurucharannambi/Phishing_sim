This project helps you deploy and use Gophish, an open-source phishing toolkit, to create real security awareness campaigns and test organizational exposure to phishing threats—hosted so anyone can access your training links globally.​

What is Gophish?
Gophish is a free, open-source framework that lets you quickly set up and manage phishing engagements with easy-to-edit templates, landing pages, and detailed tracking.​

Project Goals
Guide users in launching Gophish on a cloud VPS (AWS, DigitalOcean, Azure, etc.)

Make phishing landing pages globally accessible (not just local)

Share sample campaign templates for educational, ethical testing

Document steps needed for global hosting and secure setup

Key Features
Step-by-step global hosting setup

Creating and importing pixel-perfect templates​

Sample HTML code for realistic landing pages (like Amazon, Instagram)​

Instructions for setting up domain and SSL

Real-time tracking of email opens, clicks, and credential submissions

How to Use This Repository
Prepare a Cloud Server: Launch a Linux/Windows VM with a public IP address.

Install Gophish: Download the latest release, extract it, and run the binary.​

Configure for Public Access: Edit config.json to allow access from anywhere, open required ports (80, 443, 3333), and restart Gophish.

Set Up Templates and Landing Pages: Use provided HTML/email samples or your own; edit and preview inside Gophish’s UI.​

Connect SMTP Profile: Add a sending profile for your email campaigns.

Launch a Campaign: Select targets, templates, and landing pages, and start the campaign.

Track Results: Monitor clicks, credential capture, and exports for reporting.

Ethical Statement
This project is for security awareness, penetration testing, and authorized training only. Never deploy Gophish or any phishing page against real users without explicit permission!
