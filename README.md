# Resume Parser AI
[![My Skills](https://skillicons.dev/icons?i=python,github)](https://skillicons.dev)
## Introduction
This project introduces an advanced machine learning-enhanced tool for parsing resumes and categorizing candidates using XGBoost, Support Vector Machine (SVM), and K-Means clustering algorithms. The tool is designed to streamline the candidate selection process by automating the extraction of information from resumes and intelligently analyzing the data to identify the most qualified individuals.

## Project Files
resume_parser (1).py: The main script for extracting data from resumes, capable of identifying and processing various sections such as personal information, education, experience, and skills. The XGBboost and SVM were used for predictive modeling and K_means clustering candidates based on extracted features.

## Machine Learning Models and Analysis
- XGBoost: For predicting candidate suitability and ranking based on various features extracted from the resume.
- SVM: For high-dimensional classification tasks to categorize candidates into different job-specific groups.
- K-Means Clustering: For identifying natural groupings among candidates based on their features to aid in the segmentation of the candidate pool.

## Requirements
- Python 3.x
- Libraries: re for regular expressions, pandas for data handling, pdfplumber, python-docx, nltk for text processing, xgboost, scikit-learn for machine learning, and matplotlib, seaborn for visualization.

## Setup and Execution
1. Install Python 3.x and all the required libraries.
2. Organize the resumes in the designated folder.
3. Execute resume_parser (1).py to parse the resumes and organize the data.
4. Classify and Cluster the candidates using the trained machine learning models.
5. Analyze the output for recruitment insights, including clusters and classifications of candidates.

## Conclusion
This project's integration of regex-based parsing, data manipulation with pandas, and sophisticated machine-learning models offers a comprehensive approach to modern recruitment challenges. It not only automates the extraction of information from resumes but also utilizes advanced analytics to enhance the selection process, thereby facilitating the recruitment of top talent in an efficient and effective manner.
