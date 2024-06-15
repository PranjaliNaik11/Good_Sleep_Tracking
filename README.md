# Sleep Health Data Analysis
## Project Overview
This project involves the analysis of anonymized sleep and lifestyle metrics for 374 individuals. The dataset contains average values for each person calculated over the past six months. The analysis aims to gain insights into various factors affecting sleep health, including sleep duration, sleep quality, physical activity, stress levels, BMI categories, and the presence of sleep disorders.

## Dataset Description
The dataset is saved as sleep_health_data.csv and includes 13 columns covering various aspects related to sleep health.

| Column | Description |
|---------|----------------------------------------|  
| `Person ID` | An identifier for each individual. |
| `Gender` | The gender of the person (Male/Female). |  
| `Age` | The age of the person in years. |
| `Occupation` | The occupation or profession of the person. |
| `Sleep Duration (hours)` | The average number of hours the person sleeps per day. |
| `Quality of Sleep (scale: 1-10)` | A subjective rating of the quality of sleep, ranging from 1 to 10. |
| `Physical Activity Level (minutes/day)` | The average number of minutes the person engages in physical activity daily. |  
| `Stress Level (scale: 1-10)` | A subjective rating of the stress level experienced by the person, ranging from 1 to 10. |
| `BMI Category` | The BMI category of the person (e.g., Underweight, Normal, Overweight). |
| `Blood Pressure (systolic/diastolic)` | The average blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure. |
| `Heart Rate (bpm)` | The average resting heart rate of the person in beats per minute. |
| `Daily Steps` | The average number of steps the person takes per day. |
| `Sleep Disorder` | The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea). |


## Data Analysis Objectives
The main objectives of this analysis are:
1. Identify the occupation with the lowest average sleep duration.
2. Identify the occupation with the lowest average quality of sleep.
3. Analyze BMI categories to find users with insomnia.
4. Calculate the ratio of app users diagnosed with insomnia.

## Analysis Steps
### 1. Data Loading and Preprocessing
-Load the dataset sleep_health_data.csv.
-Inspect the data for missing values and inconsistencies.
-Handle missing values and clean the data as needed.
### 2. Descriptive Statistics
-Calculate basic statistics (mean, median, standard deviation) for each numeric column.
-Summarize the distribution of categorical columns.
### 3. Occupation Analysis
- Occupation with Lowest Average Sleep Duration:
    - Group the data by occupation.
    - Calculate the average sleep duration for each occupation.
    - Identify the occupation with the lowest average sleep duration.   
- Occupation with Lowest Average Quality of Sleep:
    - Group the data by occupation.
    - Calculate the average quality of sleep for each occupation.
    - Identify the occupation with the lowest average quality of sleep.
### 4. BMI Category and Insomnia Analysis
-Group the data by BMI category.
-Count the number of individuals diagnosed with insomnia in each BMI category.
-Identify which BMI categories have the highest prevalence of insomnia.
### 5. Insomnia Diagnosis Ratio
-Calculate the total number of individuals diagnosed with insomnia.
-Calculate the ratio of individuals diagnosed with insomnia to the total number of -individuals in the dataset.

## Results
### Occupation with Lowest Average Sleep Duration
- The occupation with the lowest average sleep duration was identified. [Details]
### Occupation with Lowest Average Quality of Sleep
- The occupation with the lowest average quality of sleep was identified. [Details]
### BMI Category and Insomnia
- The analysis revealed the prevalence of insomnia across different BMI categories. [Details]
### Insomnia Diagnosis Ratio
- The ratio of individuals diagnosed with insomnia was calculated. [Details]

## Conclusion
This analysis provides insights into the sleep health of individuals based on their occupation, BMI category, and other lifestyle metrics. The findings can help identify groups that may benefit from targeted interventions to improve their sleep health.

## How to Run the Project

1. Ensure you have the necessary libraries installed:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

2. Load the dataset `sleep_health_data.csv`.

3. Perform the data preprocessing steps to clean and prepare the data for analysis.

4. Follow the analysis steps outlined above to derive insights from the data.

5. Use the results to inform recommendations for improving sleep health among different groups.
