# UBC Course Data Analysis & Future Planning

An end-to-end analytics project that transforms historical UBC course data into an interactive decision-support dashboard for academic planning.

The project integrates BigQuery, SQL, Looker Studio, Google Vertex AI, and time-series forecasting to help university administrators optimize course offerings, monitor student performance, forecast enrollment demand, and evaluate the impact of online learning.

---

## Live Dashboard

Interactive Dashboard

https://lookerstudio.google.com/reporting/7e2e0181-9af2-43d8-9abe-8bf6526a2803

---

## Project Demo

Video Demonstration

https://drive.google.com/file/d/1L6abPBN17KL7yiWVRTUWFb3NcpMnAhQG/view?usp=share_link

---
<img width="2048" height="1279" alt="image" src="https://github.com/user-attachments/assets/391eceac-d5c1-481c-a777-e49bd7416411" />


## Business Problem

Universities face increasing challenges in allocating teaching resources efficiently while maintaining high educational quality.

Course enrollment fluctuates significantly over time, student performance varies across faculties, and the transition to online learning introduced new uncertainties regarding teaching effectiveness.

This project explores how historical academic data can be leveraged to support evidence-based course planning by answering questions such as:

- Which courses are becoming more or less popular?
- Which courses should receive additional teaching resources?
- How are different courses related through enrollment patterns?
- Which courses perform better in online learning environments?
- How can historical data improve future course planning?

---

## Project Objectives

The project aims to build an intelligent analytics platform that enables academic administrators to:

- Forecast future course enrollment
- Monitor student performance
- Detect high-risk courses
- Evaluate online learning effectiveness
- Analyze course relationships
- Support data-driven academic planning

---

## Data Source

Public UBC Course Dataset

https://github.com/DonneyF/ubc-pair-grade-data

The dataset includes historical academic records from UBC Vancouver between 1996 and 2023.

Information includes:

- Course information
- Faculty
- Academic sessions
- Student enrollment
- Grade distributions
- Instructor assignments

For this project, the analysis focuses on UBC Vancouver from 2014–2023.

---

## Technology Stack

Data Storage

- Google Cloud Storage
- BigQuery

Data Processing

- SQL
- Python
- Pandas
- Jupyter Notebook

Analytics

- ARIMA PLUS Forecasting (BigQuery ML)
- Pearson Correlation Analysis
- Google Vertex AI Sentiment Analysis

Visualization

- Looker Studio

---

## Project Workflow

1. Collect and merge historical UBC course datasets

2. Clean and standardize data using Python

3. Upload processed dataset into Google Cloud Storage

4. Transform and query data using BigQuery SQL

5. Build forecasting models using ARIMA PLUS

6. Perform sentiment analysis using Vertex AI

7. Develop an interactive dashboard in Looker Studio

8. Generate business recommendations for academic planning

---

## Dashboard Features

### Enrollment Trends

Analyze historical enrollment changes across faculties and identify:

- Fastest growing courses
- Declining courses
- Enrollment forecasts

Forecasts are generated using ARIMA PLUS in BigQuery ML.

---

### Course Correlation Analysis

Identify relationships between courses based on enrollment trends.

Positive correlations indicate courses that tend to grow together.

Negative correlations may suggest scheduling conflicts or competing specialization choices.

These insights support:

- Capacity planning
- Course scheduling
- Curriculum optimization

---

### Student Performance Analysis

Monitor:

- Fail rate
- Average grade
- Grade distribution

Identify courses requiring additional academic support.

---

### Course Review Sentiment

Course reviews are analyzed using Google Vertex AI to classify sentiment into:

- Positive
- Neutral
- Negative

Combining review sentiment with fail rates helps identify courses that may require instructional improvements.

---

### Online Learning Impact

Compare course performance across:

- Pre-COVID
- During COVID
- Post-COVID

The dashboard evaluates:

- Enrollment changes
- Average grade changes
- Online learning suitability

This helps identify which courses are better suited for hybrid or fully online delivery.

---

## Key Insights

- Several courses experienced sustained enrollment growth and are projected to continue increasing in demand.
- Strong positive enrollment correlations suggest opportunities for coordinated course scheduling and capacity planning.
- High fail-rate courses may benefit from additional academic support such as tutoring, office hours, or curriculum redesign.
- Courses with high fail rates and predominantly negative reviews represent priority areas for instructional improvement.
- Online learning effectiveness varies considerably across disciplines, indicating that delivery mode should be tailored by course characteristics rather than applied uniformly.

---

## Repository Structure

```
UBC-Course-Analytics

│
├── README.md
├── dashboard/
│   └── Looker Studio Dashboard
├── notebook/
│   └── Data Cleaning.ipynb
├── presentation/
│   └── Final Presentation.pdf
├── data/
│   └── Processed Dataset
```

---

## Limitations

- Sentiment analysis currently includes publicly available reviews for selected Faculty of Business courses only.
- Enrollment forecasting is based on historical trends and does not incorporate future curriculum or policy changes.
- COVID delivery mode is approximated using the 2020–2021 academic period.

---

## Future Improvements

Potential future enhancements include:

- Integrating official course evaluation surveys
- Expanding sentiment analysis to all faculties
- Developing instructor-level analytics
- Building AI-powered course recommendation features
- Supporting real-time dashboard updates using automated data pipelines

---

## Team

Thunder Hackers

Master of Business Analytics

UBC Sauder School of Business

- Sisly Lyu
- Lingxi Li
- Wendy Liu
- Heran Ma
- Angela Wu
