# IMDB-Movie-Rating

### Objective
The objective of this commit is to load and preprocess data from the provided IMDb dataset using Python and Pandas. The primary focus is on data cleaning, exploration, and basic analysis. The committed code includes reading the dataset, checking column information, and performing various operations such as sorting, filtering, and adding new columns to derive insights from the data.

### Changes Made
1. Loaded the IMDb dataset from a CSV file, parsing the 'release_date' column as datetime.
2. Checked the column information using the `info()` method.
3. Identified the movie with the highest revenue.
4. Extracted a list of columns, displayed the first few rows of the dataset, and checked the existence of Hindi language movies.
5. Explored movies with Hindi as the original language and filtered specific columns for analysis.
6. Filtered movies with a runtime greater than 180 minutes.
7. Filtered movies with a runtime between 150 and 180 minutes.
8. Created a new column 'Interval' representing half of the runtime.
9. Added a new column 'profit' by calculating the difference between revenue and budget.
10. Demonstrated the use of the `drop` method to remove a column temporarily and permanently.
11. Calculated and displayed the sum, mean, and mode of the 'revenue' column.
12. Identified the movie with the maximum profit and the one with the highest revenue.
13. Displayed movies with the maximum budget and the lowest revenue.
14. Set the 'imdb_id' column as the index and later reset it.
15. Created a new column 'new_title' with uppercase titles.
16. Sorted the DataFrame by runtime in descending order.
17. Used datetime functions to manipulate the 'release_date' column.
18. Checked for missing values in the 'runtime' column and filled them with 0.
19. Replaced NaN values in the 'spoken_languages' column with the string 'abc'.
20. Modified the 'status' column by replacing "Rumored" with "postponed".
21. Explored movies with a runtime greater than 120 minutes and further filtered by specific runtime ranges.

### Additional Information
- Utilized various Pandas functions such as `apply`, `sort_values`, `drop`, `fillna`, and more for data manipulation.
- Incorporated datetime functions to handle date-related operations.
- Explored and modified columns based on specific conditions.
- Checked for missing values and handled them accordingly.
- Committed the changes with clear documentation for each step.

