# AI_Data_Analayst
An AI layer that sits on top of enterprise databases and lets non-technical users query live data in plain English.

This repository contains a high-fidelity, interactive AI Data Analyst Dashboard prototype built with HTML5, CSS3, and Chart.js. Refer to the main application file ai_data_analyst.html for the full source code and implementation.

**Key Features**
Interactive Data Visualizations: Real-time rendering of line and bar charts using Chart.js, featuring dynamic color presets and exportable PNG capabilities.

AI Insight Engine: Provides automated textual summaries and business insights based on current data trends.

Trend Forecasting: A dedicated AI Forecast module that utilizes linear regression models to predict revenue for upcoming months.

Natural Language (NL) Filtering: A smart filtering system that allows users to query data tables using plain text (e.g., "amount above 50000").

Automatic Report Generator: Generates comprehensive business reports including executive summaries, metric grids, and strategic recommendations.

SQL Transparency: Automatically generates and displays the SQL queries used to fetch data from the simulated database.

Technical Stack
Frontend: HTML5, CSS3 (Modern Grid/Flexbox layouts), JavaScript (ES6+).

Charting: Chart.js (via CDN).

Typography: System fonts (San Francisco, Segoe UI).

Design: Dark-mode sidebar with a clean, high-contrast dashboard interface.

Project Structure
The single-file application is organized into the following logical panes:

Chart: The primary visual workspace.

AI Insight: Automated data storytelling and summaries.

SQL: Backend query visibility and copy-to-clipboard functionality.

Data Table: Raw data access with search and NL filter capabilities.

Forecast: Predictive analytics and trend line visualization.

Report: Formal business report generation and PDF export simulation.

Getting Started
Clone the repository to your local machine.

Open ai_data_analyst.html in any modern web browser.

Use the Smart Suggestions or the bottom Chatbar to interact with the simulated data.

Sample Data
The dashboard comes pre-loaded with a simulated database containing four tables:

sales: 500 records of transaction history.

customers: Profiles of 15 active users.

products: Inventory across electronics, furniture, and educational categories.

regions: Geographic performance data across five sectors.
