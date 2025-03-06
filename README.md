Demographic Data Analyzer
Python
Pandas

This project is a Python script that analyzes demographic data from the adult.data.csv dataset. It calculates key statistics such as race distribution, average age of men, income by education level, and more. Built using the pandas library, it is a great example of data analysis with Python.

Features
Race Distribution: Count of individuals by race.

Average Age of Men: Mean age of male individuals.

Education Analysis:

Percentage of people with a Bachelor's degree.

Income distribution for people with and without advanced education.

Work Hours Analysis:

Minimum work hours per week.

Percentage of people working minimum hours who earn more than 50K.

Country Analysis:

Country with the highest percentage of people earning more than 50K.

Occupation Analysis:

Most popular occupation for high earners in India.

Requirements
Python 3.x

pandas (pip install pandas)


Example Output
Copy
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
Dataset
The dataset used is the Adult Data Set from the UCI Machine Learning Repository. It contains demographic information such as age, education, occupation, race, and income.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.
