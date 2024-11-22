The **Fuel Factor Python Project** is a simple project that investigates the nutritional health of college students, with Fisk University students being the primary contributors to data collection. 


## About the Project
The purpose of this survey is to explore the eating habits of college students and analyze their effects on daily student performance, particularly in terms of energy levels and nutritional goals. By identifying trends in the data collected, the project provides insights into the feeding habits of students at Fisk University. 


## Features
### 1. Data Collection 
I designed an interactive and user-friendly survey to collect data on various factors believed to influence overall nutritional health. These factors include:
 - Number of exercise sessions per week.
 - Daily servings of fruits and vegetables.
 - Weekly fast-food consumption. 
 - Other key lifestyle habits. 

The collected data was stored in a Google Sheet using the `gspread` library. 

**Note**: Due to the limited number of survey responses, additional data was manually added to ensure sufficient sample size for meaningful analysis. 

### 2. Data Analysis:
Using the `pandas` library, I analyzed the collected data to uncover patterns and trends. Key functionalities utilized include: 
- Filtering rows with the `.loc()` method. 
- Summarizing data with the `.sum()` method. 
- Calculating percentage distributions with the `.value_counts()` method. ### 

### 3. Data Visualization: 
The trends observed during data analysis were visualized using the `matplotlib` library. Key visualizations include: 
- **Bar Charts**: Representing trends such as exercise sessions vs. energy levels.
 - **Pie Charts**: Highlighting distributions of factors like fruit and vegetable consumption. 
