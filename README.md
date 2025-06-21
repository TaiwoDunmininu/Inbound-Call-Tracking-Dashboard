# Inbound Call Tracking  Automation & Dashboard

## Table Content

- [Project Overview](#project-overview)
- [Features](#features)
- [Tools](#tools)
- [Step-by-Step Process](#step-by-step-process)
- [Dashboard](#dashboard)

### Project Overview

Automated Google Sheets system to track and analyze inbound call data for marketing campaigns. This project includes campaign financial tracking, client billing, daily performance metrics, and a dynamic dashboard—all fully automated using formulas and app integrations.

### Features
 
 - Google Form integration for daily data entry
 - Dynamic dashboard for client & campaign performance
 - Automatic profit and ROI calculation
 - Matrix sheet for advanced pivoting
 - Professional layout and automation-ready templates

### Tools

- Google sheet
- Google Forms
- Google Apps Script (optional)
- Formulas: QUERY, IMPORTRANGE, ARRAYFORMULA, IF, VLOOKUP, etc.
- Conditional Formatting
- Charts & Data Visualization

  
###  Step-by-Step Process

#### 1. Sheet Design & Planning
 #### Defined core tabs includes;

- Settings – client & campaign mapping
- Client Campaign Manager – campaign setup
- Daily Call Data – data from Google Form
- Client Billing – calculates billable calls and revenue
- Campaign Expenses – records ad costs
- Matrix Sheet – summary pivot logic
- Dashboard – visual KPIs
#### Mapped out data flow between sheets

#### 2. Automating Data Input

- Created Google Form for call agents to submit data daily
- Connected Form responses to Daily Call Data tab
- Used data validation for consistent entries


#### 3. Formula-Based Logic

- Applied QUERY and ARRAYFORMULA to pull data by date, campaign, and client
- Auto-calculated:
  - Revenue = Rate × Number of calls
  - Profit = Revenue - Expenses
  - ROI = Profit / Expenses
- Used VLOOKUP for rate/client lookups from Settings tab

  
#### 4. Dashboard CreationBuilt a visual dashboard using:

- Bar charts (Calls by Campaign)
- Line charts (Daily Trends)
- Scorecards (Total Revenue, Total Profit, ROI)

- Enabled dynamic filtering (by Client or Date Range)

#### 5. Testing & Optimization

- Ran dummy data through the form and sheets
- Debugged formula errors and ensured dynamic updates
- Optimized layout and conditional formatting for clarity



### Dashboard

![Inbound project](https://github.com/user-attachments/assets/3ca914b8-ba11-4afa-898d-3f23d2990889)
