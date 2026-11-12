# 🤖 AI Layoffs Analytics Dashboard

## 📌 Project Overview

The **AI Layoffs Analytics Dashboard** is a data analytics project designed to explore workforce layoffs and the potential impact of artificial intelligence across companies, industries, and time periods.

The project uses data analysis and visualization to identify layoff patterns, compare company-level trends, and communicate insights that can support informed business discussions.

> **Note:** The dashboard presents patterns in the dataset. It does not, by itself, prove that AI caused a particular layoff.

## 🎯 Project Objectives

- Analyze total layoffs across companies and industries.
- Identify companies with the highest reported layoffs.
- Explore layoff trends over time.
- Compare workforce reductions across sectors and locations.
- Examine available AI-adoption indicators alongside layoff metrics.
- Present key findings through interactive visualizations.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Interactive dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Measures and calculated metrics |
| Excel / CSV | Dataset storage and preparation |

## 📊 Dashboard Features

### Key Performance Indicators
Depending on the fields available in the dataset, the dashboard may include:
- Total companies analyzed
- Total employees laid off
- Average layoffs
- Net hiring
- Average AI adoption
- Layoffs by industry or company

### Visual Analysis
- Layoffs by company
- Layoffs by industry
- Layoff trends over time
- Geographic comparisons, where location data is available
- AI adoption and workforce metrics
- Interactive slicers and filters

## 🔄 Data Analysis Workflow

1. **Data Import:** Load the layoffs dataset into Power BI.
2. **Data Cleaning:** Review missing values, duplicates, inconsistent labels, and data types using Power Query.
3. **Data Transformation:** Prepare date, company, industry, and location fields for analysis.
4. **Data Modeling:** Organize relationships between tables when multiple tables are used.
5. **DAX Measures:** Create measures for totals, averages, and comparisons.
6. **Visualization:** Build KPI cards, charts, and interactive filters.
7. **Insights:** Interpret trends while considering the dataset's coverage and limitations.

## 💡 Skills Demonstrated

- Data Cleaning and Transformation
- Power Query
- DAX
- Data Modeling
- KPI Development
- Data Visualization
- Exploratory Data Analysis
- Business Intelligence

## 📷 Dashboard Preview

Add screenshots of your dashboard to the `images` folder and update the paths below.

```markdown
![AI Layoffs Dashboard](images/ai-layoffs-dashboard.png)
```

## 📁 Suggested Project Structure

```text
AI-Layoffs-Analytics/
│
├── Dataset/
│   └── ai_layoffs.csv
│
├── Dashboard/
│   └── AI_Layoffs_Dashboard.pbix
│
├── images/
│   └── ai-layoffs-dashboard.png
│
└── README.md
```

*Adjust the example file and folder names to match your repository.*

## 🚀 How to Use

1. Clone or download this repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` dashboard file.
4. If prompted, connect or update the dataset source.
5. Refresh the data and explore the report using its slicers and filters.

## 🔮 Future Enhancements

- Add regularly updated layoffs data from reliable sources.
- Compare layoffs with hiring and job-posting trends.
- Explore AI adoption by industry and company.
- Add time-based trend analysis and forecasting where appropriate.
- Build a Python-based exploratory analysis alongside the Power BI report.

## ⚠️ Data & Interpretation Disclaimer

Layoff records and AI-adoption metrics can vary by source, reporting period, and definition. A relationship between AI adoption and layoffs should not be interpreted as proof of causation. Verify data sources and document the dataset's coverage before drawing conclusions.

## 👨‍💻 Author

**Ram Vidhura Reddy P**

Data Analytics | Power BI | Python | SQL | Advanced Excel

## ⭐ Acknowledgement

This project was developed as part of my data analytics learning journey to build practical skills in data preparation, business intelligence, and interactive dashboard development.

If you find this project useful, consider giving the repository a ⭐ star!
