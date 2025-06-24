# automated-kpi-reporter
An automation workflow built with n8n that pulls data from Google Sheets (or a database), calculates daily or weekly KPIs (e.g., sales, conversions, uptime), formats the metrics, and automatically sends reports to stakeholders via Gmail or Slack. Ideal for teams that want hands-free reporting and real-time performance tracking.
# 📈 Automated KPI Report Generator using n8n

![n8n](https://img.shields.io/badge/Built%20with-n8n-5e5df0?logo=n8n&logoColor=white)
![License](https://img.shields.io/github/license/ShivaRama1414/automated-kpi-reporter)

This project automates the generation and delivery of Key Performance Indicator (KPI) reports using [n8n](https://n8n.io/). It pulls data from Google Sheets or a database, calculates business metrics like sales, conversion rates, or uptime, and sends the report to stakeholders via Gmail or Slack—automatically, on a schedule.

---

## 📸 Workflow Screenshot

![KPI Workflow](<img width="1465" alt="Automated KPI Repor Genearator" src="https://github.com/user-attachments/assets/42072c88-a42c-47ae-b934-fc80761e4b09" />
./screenshots/kpi_workflow.png)

> Ensure this image is saved in: `screenshots/kpi_workflow.png`

---

## 🚀 Features

- 🕒 Scheduled KPI delivery (daily or weekly) using **Cron**
- 🔗 Connects to **Google Sheets** or **SQL databases**
- 📊 Calculates important metrics like:
  - Total Sales
  - Conversion Rate
  - Uptime %
  - Growth over time
- ✉️ Sends formatted reports through **Gmail** or **Slack**
- 🧩 Easily extendable with more KPIs or delivery methods

---

## 🧰 Tech Stack

- **n8n** – Workflow automation
- **Google Sheets API** or **MySQL/PostgreSQL**
- **Function Node** – Business logic & calculations
- **Gmail / Slack Nodes** – Report delivery
- **JavaScript** – Inside function node for KPI logic

---

## 📁 Project Structure

