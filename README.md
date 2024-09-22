# Movie Analysis with Python - Data Cleaning and Exploration

This project performs data cleaning, exploratory data analysis, and insights extraction on a movie dataset using Python and libraries such as Pandas and NumPy.

## Project Overview
**The aim of this project is to:**
1. Clean the movie dataset by handling missing values and removing unnecessary columns.
2. Analyze the dataset to derive useful insights, such as the top-grossing movies, popular genres, and critically acclaimed actors.

## Tasks Overview

### Task 1: Reading and Inspection
- **Subtask 1.1:** The movie dataset is imported and stored as a Pandas DataFrame.
- **Subtask 1.2:** The DataFrame is inspected for its shape, column types, and basic information. The dataset contains 5,043 rows and 28 columns.

### Task 2: Cleaning the Data
- **Subtask 2.1:** Missing values are inspected for both rows and columns.
- **Subtask 2.2:** Unnecessary columns such as Facebook likes and content rating are dropped.
- **Subtask 2.3 - 2.5:** Rows with significant missing data are dropped, while missing values in the 'language' column are filled with "English". After cleaning, 77% of the rows are retained.
- **Subtask 2.6:** The retained number of rows is checked.

### Task 3: Data Analysis
- **Subtask 3.1:** Budget and gross revenue are converted to millions for easier interpretation.
- **Subtask 3.2:** The top 10 highest-grossing movies are found, with 'Avatar' leading the list.
- **Subtask 3.3:** Duplicate values are removed, ensuring accurate data analysis.
- **Subtask 3.4:** The IMDb Top 250 movies are extracted based on the number of votes and IMDb score. A separate list of top non-English films is also created.
- **Subtask 3.5:** The top 10 directors with the highest average IMDb score are identified, with Akira Kurosawa and Charles Chaplin ranking highly.
- **Subtask 3.6:** The most popular genre combinations (Family + Sci-Fi) are identified based on their gross revenue.
- **Subtask 3.7:** Leonardo DiCaprio emerges as both the critic-favorite and audience-favorite actor based on average reviews.

## Conclusion
This analysis demonstrates how data cleaning and exploratory data analysis can provide valuable insights from a movie dataset, such as identifying top-grossing films, popular genres, and renowned directors and actors.

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
