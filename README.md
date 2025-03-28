# MRP Project
<h1>Streamlining Recruitment for Startups through Analytics</h1>
📊  Optimizing hiring strategies with AI-powered analytics

<h2>Project Description</h2>
This Power BI dashboard provides key insights into recruitment analytics, helping startups optimize hiring strategies, reduce costs, and improve candidate quality. Key features include:

Recruitment campaign performance tracking

Cost-per-hire analysis

Interactive data visualization

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
git clone https://github.com/brajesh514/powerbi-recruitment-dashboard.git<br>
cd powerbi-recruitment-dashboard
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
-Generate synthetic data:
<p>Code:
python generate_data.py</p>

## Usage
Run the Python script to generate synthetic data, then load it into Power BI:
<p>Code:
python generate_data.py</p>
-Import data files into Power BI.
-Load the RecruitmentDashboard.pbix file.

## Data Sources

The dashboard integrates the synthetic dataset generated above. In real-world applications, it can be combined with:

Job postings APIs (LinkedIn, Indeed, Glassdoor)

HR and employer reports
## Features
✔ Real-time job market insights with interactive filters<br>
✔ Hiring trends analysis (heatmaps, line charts, and bar charts)<br>
✔ Salary benchmarking across industries and experience levels<br>
✔ In-demand skills tracking to align with market needs<br>

## Project Structure
<p>powerbi-recruitment-dashboard/<br>
├── data/<br>
│   ├── recruitment_data.xlsx<br>
├── dashboard/<br>
│   ├── RecruitmentDashboard.pbix<br>
├── images/<br>
│   ├── dashboard-preview.png<br>
├── README.md<br>
└── LICENSE<br>

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
