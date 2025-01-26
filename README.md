# Personalized Student Recommendations for Quiz Performance

## Project Overview

This project is designed to analyze quiz performance data of students and provide personalized recommendations to improve their preparation.The system generates insights that help pinpoint the student's strengths and weaknesses.

The project is built using Python.

### Key Features:
- Analyze quiz performance over multiple attempts.
- Identify weak areas based on incorrect responses.
- Personalized recommendations for improving performance.
- Data visualization of trends like scores and speed over time.

## Approach

1. **Data Ingestion**: 
   - The project uses two datasets: 
     - *** Quiz Data**: Latest quiz submissions by students.
     - **Historical Quiz Data**: Performance data for the last 5 quizzes for each student.
   - The data is converted  into a Pandas DataFrame from a API endpoint.

2. **Data Processing**: 
   - Before converting into dataframe its normalized using json_normalise.
   - The missing values are handled.


3. **Visualization**: 
   -  Interactive charts and graphs are generated to give students visual feedback on their performance.

---

## Setup Instructions

 1. **Requirements.txt**: file contains the necessary libraries to be installed 
 2. **Python** :version of above 3.1.11

### 1. Clone the repository

git clone 