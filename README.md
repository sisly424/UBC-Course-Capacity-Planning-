#### Project Overview ####

This project leveraged a dataset of info. about past courses in UBC from GitHub to explore patterns and insights about course enrollment & forecasting, correlations, review analysis and online course effectiveness. Deliverables include an interactive dashboard showing key data and actionable recommendations for UBC course administration department.


#### Dataset Overview ####

This dataset is from GitHub: https://github.com/DonneyF/ubc-pair-grade-data/tree/a6b5b0fe4a02cbcc7e9591624abd5611b50f85ce

This dataset mainly covers:
- Courses in UBCV and UBCO since 1996 - 2023.
- Course Details (Faculty, Year & Session, etc)
- Course Enrollments
- Student Grade Distributions (A+, A, A-, B+, etc)
- Instructor assignments


#### Project Assumptions ####

1. This project was only focusing on data between 2014-2023 in Vancouver Campus.

2. Since UBC officially announced to turn to fully virtual study mode in 2020, and recovered to in person classes at the end of 2021. We assumed that all courses during 2020-2021 were conducted virtually.



#### Video Demo ####

1. Due to time limit, only reviews for courses under Faculty of Business was collected. Therefore the sentiment summary would only work for part of courses under faculty of business. However, in real deployment, we recommend UBC to use responses of post course evaluation questionnaires as the review data for better sentiment analysis.

2. Due to time limit, correlation analysis by enrollment was conducted on all courses in faculty of business. Correlation analysis by fail rate and average score were conducted on top 10 popular (calculated based on number of enrollment) courses under faculty of business.


#### Team Members ####

Master of Business Analytics 2025 | UBC Sauder School of Business

Sisly Lyu, Lingxi Li, Wendy Liu, Heran Ma, Angela Wu


