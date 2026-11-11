# SOAR-EDR-Automation-project-
SOAR EDR Automation with Tines , Slack, LaZagne Hacktool &amp; LimaCharlie for asking user to isolate the machine or not.
Overview
Automates incident response using:

LimaCharlie EDR
Tines SOAR
Slack
Email
Analyst Approval
Automated Sensor Isolation
Features

✔ Receive LimaCharlie Detection

✔ Send Slack Alert

✔ Send Email Alert

✔ Analyst Approval Page

✔ One-click Sensor Isolation

✔ Notification when isolation is declined

Architecture
(insert architecture image)

Workflow
LimaCharlie detects malicious activity
Webhook sends detection to Tines
Slack notification sent
Email notification sent
Analyst receives approval page
If YES → Sensor isolated → Slack confirmation
If NO → Slack notification only
Technologies
LimaCharlie
Tines
Slack API
REST APIs
