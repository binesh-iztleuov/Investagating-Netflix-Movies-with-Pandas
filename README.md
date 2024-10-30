# Investagating-Netflix-Movies-with-Pandas
This project perform exploratory data analysis on the netflix_data.csv data to understand more about movies from the 1990s decade.

## Project Goals
- Identify the most frequent movie duration in the 1990s
- Identify the number of short movies in the 1990s

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Analysis Methods
1. **Data Loading**:
   - Imported pandas as pd
   - Loaded netflix_data.csv file by using `pd.read_csv()`
2. **Data Preprocessing**:
   - Got an overview of data by using `df.head()` and `df.info()`
3. **Data Filtering**:
   - Applied various filters to analyze specific genres, release year and duration.
   - Used conditional statements to create new columns based on existing data.
4. **Data Aggregation and Frequency Analysis**:
   - Used `count()` to count number of short films in a certain period of time
   - Applied `value_counts()` to analyze the frequency of different durations in a certain period of time

## Key Findings
1. The most frequent movie duration in the 1990s is 94 minutes. There were 7 films with this duration
2. There were 7 short action movies (less than 90 minutes) released in the 1990s
