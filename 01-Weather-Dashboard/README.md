# 🌤️ Weather Dashboard

An automated weather reporting workflow built with n8n that retrieves live weather data, stores it in Google Sheets, and emails a formatted weather report automatically.

---

## Features

- Runs automatically on a schedule
- Retrieves live weather data from a Weather API
- Formats the weather information
- Saves weather records to Google Sheets
- Sends a formatted weather report via Gmail

---

## Technologies

- n8n
- Weather API
- Google Sheets
- Gmail

---

## Workflow

Schedule Trigger

↓

Weather API

↓

Format Weather Report

↓

Append Weather Data to Google Sheets

↓

Send Weather Report

---

## Complete Workflow

![Workflow](screenshots/Workflow.png)

---

## Weather API

Retrieves the latest weather information.

![Weather API](screenshots/weather-api.png)

---

## Format Weather Report

Formats the API response into a readable weather report.

![Format Weather Report](screenshots/Format-Weather-Report.png)

---

## Append Weather Data to Google Sheets

Stores each weather report for future reference.

![Google Sheets](screenshots/Append-weather-data-to-Google-Sheets.png)

---

## Send Weather Report

Automatically emails the weather report to the recipient.

![Send Weather Report](screenshots/Send-Weather-Report.png)
