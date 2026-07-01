![n8n](https://img.shields.io/badge/n8n-Automation-orange?style=for-the-badge&logo=n8n)
![Gemini](https://img.shields.io/badge/Google-Gemini-blue?style=for-the-badge&logo=google)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-green?style=for-the-badge&logo=googlesheets)
![REST API](https://img.shields.io/badge/REST-API-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

# 🚀 AI Job Search Automation

An AI-powered job search automation platform that aggregates software engineering jobs from multiple sources, filters opportunities based on user-defined criteria, enriches job postings using AI, and stores structured results for tracking and analysis.

## 📌 Overview

Searching for jobs across multiple career sites is repetitive and time-consuming. This project automates the process by collecting job postings, filtering them based on configurable preferences, extracting useful information, and organizing the results into Google Sheets.

The workflow is built using **n8n** and integrates multiple APIs and cloud services to create a configurable job aggregation pipeline.

---

## ✨ Features

- Search jobs using configurable keywords
- Read search filters from Google Sheets
- Collect job postings from multiple sources
- Filter jobs by location and user preferences
- Remove duplicate job listings
- Extract structured job information
- AI-powered job analysis using Google Gemini
- Store processed jobs in Google Sheets
- Easily extendable with additional job sources

---

## 🛠️ Tech Stack

- n8n
- Google Sheets API
- Google Drive API
- Google Gemini API
- REST APIs
- JavaScript
- JSON

---

## 📂 Project Structure

```
AI-Job-Search-Automation/
│
├── workflow/
│   └── AI-Job-Search-Automation.json
│
├── screenshots/
│
├── docs/
│
├── sample-data/
│
└── README.md
```

---

## ⚙️ Workflow

1. Load search filters from Google Sheets
2. Generate search URLs
3. Retrieve job postings
4. Extract job details
5. Normalize job data
6. Analyze job descriptions using Gemini AI
7. Save structured results to Google Sheets

---

## 🚀 Future Improvements

- Greenhouse API integration
- Lever API integration
- Workday support
- Company career page integration
- Advanced duplicate detection
- AI-based job ranking
- Dashboard for job analytics

---

## 📄 License

This project is intended for educational and portfolio purposes.
