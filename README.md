# JobPulse-PowerBI-Dashboard

This project showcases a full Power BI data analysis pipeline using job market data from Wuzzuf. The goal is to extract insights into hiring trends, in-demand skills, and job roles in Egypt.

🔗 [Live Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiYjY2ZmY0NDYtOGM0OS00MjI3LWEwZjItMDUzY2ExMDJmNDczIiwidCI6IjhjMWFlYThiLTJmMzQtNDk5NS1hMTY0LTQzYmM3YjZlYTczNyJ9)

## Dashboard Features

- **Job Posting Trends**: Track volume over time.
- **Top Skills in Demand**: Aggregated view of required skills.
- **Experience Levels**: Analysis of job requirements.
- **Interactive Filters**: Position level, year, and skills.

## Dataset

- Source: [Wuzzuf Egypt Job Postings]
- Format: CSV
- Records: 25,000+ job listings
- Fields: Job Title, Job Skills, Years of Experience, Number of Applicants, etc.

## Data Transformation Steps

All Power Query steps are documented in detail:
- Remove blanks and nulls
- Clean and normalize job skills
- Split skills into rows
- Extract Year/Month from date

👉 See [View Full Transformation Documentation (PDF)](documentation/JobPulse_Transformation_Documentation.pdf)

## Project Files

- `documentation/`: Transformation steps and project rubric
- `data/`: Raw dataset 

