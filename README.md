# capstone-
An explainable decision-support system for hostel food quality and grievance redressal
# Hostel Grievance & Food Feedback System

## Overview

A complete feedback and redressal system for a university
hostel using Google Apps Script and Google Sheets.

The system handles:

- Food feedback
- Electrical complaints
- Plumbing complaints
- Wi-Fi complaints
- Security complaints
- Ragging-related complaints
- Administrative complaints

## Key Features

- Mobile-friendly web interface
- Food feedback through QR codes
- Complaint registration
- Complaint tracking
- SLA-based escalation
- Warden dashboard
- Email alerts
- Analytics
- Privacy-aware identity handling
- Safety complaint fast-path
- Google Sheets as the database

## Architecture

Student
↓
HTML Web App
↓
Google Apps Script
↓
Google Sheets
↓
Dashboard / Email Alerts

## Technologies Used

- Google Apps Script
- HTML
- JavaScript
- Google Sheets
- Gmail
- Google Drive
- Naive Bayes
- Statistical analysis

## Project Structure

| File | Purpose |
|---|---|
| Code.gs | Routing, authentication, database setup |
| Feedback.gs | Food feedback processing |
| Complaints.gs | Complaint and SLA management |
| Analytics.gs | Classification and analytics |
| Api.gs | Dashboard, email and triggers |
| Index.html | Meal feedback |
| Complaint.html | Complaint submission |
| Track.html | Complaint tracking |
| Dashboard.html | Staff dashboard |
| Menu.html | Menu management |

## Deployment

1. Create a Google Spreadsheet.
2. Open Extensions → Apps Script.
3. Add the project files.
4. Run `setupSystem()`.
5. Authorize the application.
6. Deploy as a Web App.
7. Configure the Config and Roles sheets.
8. Generate QR codes.
9. Test the application.

## Privacy

The system uses pseudonymous identity handling and
PII redaction before storing comments.

## Limitations

- Apps Script execution limits
- Google Sheets scalability limits
- Initial classifier accuracy depends on training data
- Native-language classification requires additional training
- Outcome measurement is associational rather than causal

## Project Status

Under Development
