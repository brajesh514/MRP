# MRP Project
<h1>Data Talent Tracker</h1>
📊  A Power BI Dashboard for Job Market Analysis and Skills Tracking

<h2>Project Description</h2>
The Data Talent Tracker is an interactive Power BI dashboard designed for HR professionals, recruiters, and job seekers to analyze job market trends, in-demand skills, and salary benchmarks. The dashboard provides data-driven insights to help organizations make informed hiring decisions and for job seekers to align their skills with market demands.
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Features](#features)
- [Project Structure](#project-structure)
- [Live Dashboard](#live-dashboard)
- [Contributing](#contributing)

## Installation
To set up the project locally, follow these steps:
<br>
-Clone the repository
<p>Code:
git clone https://github.com/brajesh514/DataTalentTracker.git<br>
cd DataTalentTracker
</p>
-Create and activate a virtual environment
<p>Code:
python -m venv venv  <br>
source venv/bin/activate  # macOS/Linux  
venv\Scripts\activate  # Windows  
</p>
-Install dependencies
<p>Code:
pip install -r requirements.txt  
</p>
-Generate synthetic job market data:
<p>Code:
python generate_data.py</p>

## Usage
Run the Python script to generate synthetic job market data, then load it into Power BI:
<p>Code:
python generate_data.py</p>
-Import synthetic_job_data.csv into Power BI.
-Load the JobMarketDashboard.pbix file.
-Interact with the Job Market Analysis, Skills Dashboard, and Time-Series Trends tabs.

## Data Sources

The dashboard integrates the synthetic dataset generated above. In real-world applications, it can be combined with:

Job postings APIs (LinkedIn, Indeed, Glassdoor)

Government labor data (BLS, ONS)

HR and employer reports
## Features
✔ Real-time job market insights with interactive filters<br>
✔ Hiring trends analysis (heatmaps, line charts, and bar charts)<br>
✔ Salary benchmarking across industries and experience levels<br>
✔ In-demand skills tracking to align with market needs<br>

## Project Structure
DataTalentTracker/  
├── data/                     # Data sources and processing scripts  
├── src/                      # Main application code  
│   ├── dashboard.py          # Dashboard logic  
│   ├── visualizations/       # Chart components  
├── templates/                # HTML templates (if applicable)  
├── static/                   # CSS and JavaScript files  
├── requirements.txt          # Dependencies  
├── README.md                 # Documentation  
└── LICENSE                   # Licensing information  
## Live Dashboard
🔗 View the interactive Power BI dashboard here:
<br>
👉 View Dashboard

## Contributing
We welcome contributions! Please:

Fork the repository

Create a feature branch (git checkout -b feature-name)

Commit changes (git commit -m "Added new feature")

Push to the branch (git push origin feature-name)

Submit a pull request
