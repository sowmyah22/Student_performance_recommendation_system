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
     - **Quiz Data**: Latest quiz submissions by students.
     - **Historical Quiz Data**: Performance data for the last 5 quizzes for each student.
   - The data is converted  into a Pandas DataFrame from a API endpoint of json format.

2. **Data Processing**: 
   - Before converting into dataframe its normalized using json_normalise.
   - The missing values are handled.


3. **Visualization**: 
   -  Interactive charts and graphs are generated to give students visual feedback on their performance.
      
    ![Image](https://github.com/user-attachments/assets/b9305c59-4b7c-4b57-bdb8-e41729cd2977)
   
   - This plot depicts how a user has performed in various quizzes . How the accuracy varies is dfferentiated with different levels like "High,Medium,Low"

     ![Image](https://github.com/user-attachments/assets/911368f4-49b8-4198-ab95-9df87599416a)
   - This plot visualises the percentage of questions correctly answered for a single quiz. It shows that 80% the student has answered correctly and 20% incorrectly 
  
   - Trend Analysis in performance
     ![Image](https://github.com/user-attachments/assets/aebebb63-6ac2-494d-962b-3eb86913611b)

   - The trend plot shows an increasing trend with significant fluctuations in scores towards the end of the period while the performance is improving over time
   - The fluctuations might be for various reasons like time the quiz was conducted,health conditions,level of difficulty in the questions,study habits or 
     external events.

     ![Image](https://github.com/user-attachments/assets/ed3dc209-51f7-47ba-b3d6-7a2d8deebaeb)
     
   - the above plot there is a sharp increase in the speed in the begining of the period following there is significant dips in the speed .
   - Speed is fluctuating when the quizes taken are in consecutive days and the same day
   -  But there are several days reaching speed to 100 and others almost on the higher side of speed

---

## Setup Instructions

 1. **Requirements.txt**: file contains the necessary libraries to be installed 
 2. **Python** :version of above 3.1.11

### 1. Clone the repository

git clone :https://github.com/sowmyah22/Student_performance_recommendation_system.git
