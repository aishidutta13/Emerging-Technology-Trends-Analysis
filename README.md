# Emerging Technology Trends Analysis

This project analyzes global developer survey data to identify current technology usage, future technology demand, and developer demographic patterns.

The goal is to transform raw survey data into a dashboard-ready format and use it to understand which programming languages, databases, platforms, and frameworks are currently popular and which technologies developers want to work with in the future.

## Project Overview

Developer survey datasets often contain multi-value fields such as programming languages, databases, platforms, and frameworks. This project cleans and restructures that data so it can be analyzed more effectively.

The project includes data preparation, transformation, dashboard-ready sample data, and a final dashboard PDF.

## Dashboard

The final dashboard is included as a PDF file in this repository:

```text
dashboardfinal.pdf
```

Open `dashboardfinal.pdf` to view the complete dashboard.

## Files in This Repository

```text
dashboard.ipynb              Jupyter Notebook for data cleaning and dashboard data preparation
final_dashboard_sample.csv   Dashboard-ready sample dataset
dashboardfinal.pdf           Final dashboard visualization
README.md                    Project documentation
```

## Objectives

- Analyze current technology usage among developers.
- Identify future technology trends and preferences.
- Understand developer demographics such as age, country, and education.
- Clean and transform multi-value survey fields.
- Convert raw survey data into a structured dashboard-ready format.
- Present insights through an IBM Cognos-style dashboard.

## Dataset

The project uses a developer survey dataset.

The raw dataset includes multi-value fields where one response may contain several technologies, for example:

```text
Python;JavaScript;SQL
```

These fields were transformed into a long-format structure so each technology can be analyzed individually.

A sample dashboard-ready dataset is included:

```text
final_dashboard_sample.csv
```

The full dataset can be regenerated using the notebook.

## Tools and Technologies

- Python
- Pandas
- Jupyter Notebook
- IBM Cognos Analytics
- CSV data processing
- Dashboard reporting

## Data Processing Workflow

### Data Cleaning

- Handled missing values.
- Removed inconsistencies in survey responses.
- Standardized technology and demographic fields.
- Prepared raw data for transformation.

### Data Transformation

- Split multi-value fields into individual rows.
- Converted wide-format survey responses into long-format data.
- Created structured fields for technology category, usage type, and demographic information.
- Combined worked-with technologies, desired technologies, and demographic fields into dashboard-ready data.

### Dashboard Preparation

- Created a final sample dataset for dashboard building.
- Prepared fields for technology usage analysis.
- Prepared fields for future trend analysis.
- Prepared demographic fields for comparison and segmentation.

## Dashboard Sections

### Current Technology Usage

Shows technologies developers currently work with, including:

- Programming languages
- Databases
- Platforms
- Web frameworks

### Future Technology Trends

Shows technologies developers want to work with in the future, helping identify demand and growth potential.

### Developer Demographics

Shows respondent distribution by:

- Age group
- Country
- Education level

## Key Insights

### Popular Technologies

JavaScript, SQL, and Python are among the most widely used technologies, showing strong relevance across developer roles.

### Cloud Platform Demand

Cloud platforms such as AWS, Azure, and Google Cloud show strong usage and future demand, highlighting the importance of cloud skills.

### Framework Adoption

Modern frameworks such as React and Node.js show strong adoption among developers.

### Developer Demographics

A large share of developers fall within the 25-34 age group, suggesting that the industry is strongly represented by early and mid-career professionals.

## How to Use This Project

Clone the repository:

```bash
git clone https://github.com/aishidutta13/Emerging-Technology-Trends-Analysis.git
cd Emerging-Technology-Trends-Analysis
```

Open the notebook:

```text
dashboard.ipynb
```

Run the notebook cells to view the data cleaning and transformation process.

Open the dashboard file:

```text
dashboardfinal.pdf
```

Use the sample dataset:

```text
final_dashboard_sample.csv
```

## Project Structure

```text
Emerging-Technology-Trends-Analysis/
│
├── dashboard.ipynb
├── final_dashboard_sample.csv
├── dashboardfinal.pdf
└── README.md
```

## Current Limitations

- Only a sample dashboard-ready dataset is included due to file size limits.
- The dashboard is provided as a PDF, not as a live interactive web dashboard.
- Raw survey data may need to be regenerated or downloaded separately.
- Some multi-value fields require careful transformation before analysis.

## Future Improvements

- Add dashboard screenshots directly to the README.
- Add more detailed trend comparisons between current and desired technologies.
- Include year-over-year analysis if multiple survey years are available.
- Build an interactive dashboard using Streamlit, Plotly, or Power BI.
- Add automated data cleaning scripts.
- Add more detailed documentation for recreating the full dataset.

## Conclusion

This project demonstrates a complete data analytics workflow from raw developer survey data to dashboard-ready insights. It highlights practical skills in data cleaning, transformation, dashboard preparation, and technology trend analysis.

## Author

Aishi Dutta

GitHub: [aishidutta13](https://github.com/aishidutta13)
