# SleepInc - Sleep Data Analysis

## Project Overview

Sleep is essential for physical and mental well-being, playing a key role in cell repair, memory consolidation, disease prevention, and more. As a data science consultant for SleepInc, a sleep-tracking startup, your mission is to analyze anonymous sleep data collected from their SleepScope app. The goal of this analysis is to uncover insights into how lifestyle factors such as exercise, occupation, gender, and health metrics impact sleep quality and duration.

The analysis will help SleepInc better understand the relationships between lifestyle factors and sleep patterns, providing actionable insights that could improve their product and help users achieve better sleep.

## Data Description

The dataset consists of anonymized sleep and lifestyle data for 374 individuals, collected over the past six months through the SleepScope app. It includes 13 columns of data, covering various aspects of sleep health and lifestyle factors:

| Column Name                        | Description                                                             |
|------------------------------------|-------------------------------------------------------------------------|
| `Person ID`                        | A unique identifier for each individual.                                |
| `Gender`                           | The gender of the individual (Male/Female).                             |
| `Age`                              | The age of the individual (in years).                                   |
| `Occupation`                       | The profession of the individual.                                       |
| `Sleep Duration (hours)`           | The average number of hours the individual sleeps per day.              |
| `Quality of Sleep (scale: 1-10)`   | A subjective rating of sleep quality (1 to 10 scale).                  |
| `Physical Activity Level (minutes/day)` | The average number of minutes per day the person engages in physical activity. |
| `Stress Level (scale: 1-10)`       | A subjective rating of stress levels experienced by the individual (1 to 10 scale). |
| `BMI Category`                     | The BMI category of the individual (Underweight, Normal, Overweight, etc.). |
| `Blood Pressure (systolic/diastolic)` | The individual's average blood pressure readings (systolic/diastolic). |
| `Heart Rate (bpm)`                | The individual's average resting heart rate (in beats per minute).     |
| `Daily Steps`                     | The average number of steps taken per day by the individual.           |
| `Sleep Disorder`                   | Indicates if the individual has a sleep disorder (None, Insomnia, Sleep Apnea). |

## Objectives

The key goals of this analysis are as follows:

- Identify which occupation has the lowest average sleep duration.
- Determine the profession where individuals tend to sleep the least on average.
- Identify which occupation has the lowest average sleep quality.
- Analyze the average sleep quality across occupations to find which profession experiences the lowest quality of sleep.
- Compare the occupations with the lowest sleep duration and sleep quality.
- Determine if the same occupation has both the lowest sleep duration and sleep quality.
- Examine how BMI Category affects the likelihood of insomnia.
- Calculate the ratio of individuals in each BMI category who have been diagnosed with insomnia.

## Tasks Breakdown

### Task 1: Occupation with the Lowest Average Sleep Duration
Analyze the dataset to find the occupation with the lowest average sleep duration.

### Task 2: Occupation with the Lowest Average Sleep Quality
Identify the occupation with the lowest average sleep quality and see if it matches the occupation with the lowest sleep duration.

### Task 3: Sleep Quality vs. Sleep Duration Comparison
Determine whether the occupation with the lowest average sleep duration also has the lowest average sleep quality and save the result as a boolean variable.

### Task 4: BMI Category and Insomnia Analysis
Calculate the ratio of individuals diagnosed with insomnia in each BMI category. The results will be stored in a dictionary where the keys are BMI categories and the values are the corresponding ratios.

## Tools and Libraries

This analysis will be performed using the following Python libraries:

- **pandas** for data manipulation and analysis.
- **numpy** for numerical operations.
- **matplotlib** or **seaborn** for data visualization.

## Results and Insights

- **Lowest Average Sleep Duration**: Sales Representative
- **Lowest Average Sleep Quality**: Sales Representative
- **Same Occupation for Both?**: True
- **BMI and Insomnia Ratios**: {'Normal': 0.04, 'Obese': 0.4, 'Overweight': 0.43}

