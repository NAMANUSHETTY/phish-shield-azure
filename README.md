# phish-shield-azure
“Smart Fraud Detector for UPI Payments using Microsoft Azure”.

Problem Statement

With the rapid adoption of UPI in India, frauds such as fake payment screenshots, malicious QR codes, and phishing links are increasing.
Most users—especially in rural and semi-urban areas—are vulnerable and often realize fraud only after losing money.
There is a pressing need for a proactive fraud detection system to ensure safe digital transactions.

Proposed Solution

Phish Shield is a mobile app + browser extension that protects users by detecting UPI-related fraud in real-time.
It scans QR codes, payment links, and uploaded screenshots to verify authenticity.
Using Microsoft Azure AI + Security services, it alerts users instantly before a transaction is completed.

Key Features:

QR Code Scanner → Validates if the QR belongs to a genuine UPI handle.
Link Checker → Identifies phishing or malicious URLs.
Fake Screenshot Detector → AI detects edited or fake payment proofs.
Instant Alerts → Displays “Fraud Suspected ❌” or “Safe ✅”.
Scam Reporting Ledger → Stores reported frauds for future prevention.

Tech Stack (Azure Services)

Frontend → Android (Kotlin/Flutter), Browser Extension (JS)
Backend → Python, FastAPI/Flask
Azure Services:
Azure Cognitive Services (OCR + Computer Vision)
Azure Machine Learning (fraud pattern detection)
Microsoft Defender for Cloud Apps (malicious link detection)
Azure Functions (Serverless APIs)
Azure SQL Database / Azure Blockchain (scam reporting)
Azure AD B2C & Entra ID (secure authentication)
Azure Key Vault (API keys & secrets)

WorkFlow Diagram

![Workflow Diagram](https://github.com/NAMANUSHETTY/phish-shield-azure/blob/main/Phish%20Shield%20Fraud%20Detection%20Flowchart.png?raw=true)

