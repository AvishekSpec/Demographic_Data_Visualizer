# Demographic Data Analyzer

A Python-based project to analyze demographic data and calculate key statistics such as income distribution, education levels, and work patterns.

---

## Description
This project analyzes demographic data from the `adult.data.csv` dataset. It uses Python and the `pandas` library to calculate various statistics, including:
- Distribution of races.
- Average age of men.
- Percentage of people with a Bachelor's degree.
- Income distribution based on education level.
- Country with the highest percentage of high earners.
- Most popular occupation for high earners in India.

This project is ideal for learning data analysis with Python and exploring real-world datasets.

---

## Features
- **Race Distribution**: Count of individuals by race.
- **Average Age of Men**: Mean age of male individuals.
- **Education Analysis**:
  - Percentage of people with a Bachelor's degree.
  - Income distribution for people with and without advanced education.
- **Work Hours Analysis**:
  - Minimum work hours per week.
  - Percentage of people working minimum hours who earn more than 50K.
- **Country Analysis**:
  - Country with the highest percentage of people earning more than 50K.
- **Occupation Analysis**:
  - Most popular occupation for high earners in India.

---

## Output
race_count: White                 27816
Black                  3124
Asian-Pac-Islander     1039
Amer-Indian-Eskimo      311
Other                   271
Name: race, dtype: int64
average_age_men: 39.4
percentage_bachelors: 16.4
higher_education_rich: 46.5
lower_education_rich: 17.4
min_work_hours: 1
rich_percentage: 10.0
highest_earning_country: United-States
highest_earning_country_percentage: 23.6
top_IN_occupation: Prof-specialty
