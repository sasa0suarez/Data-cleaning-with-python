# Data-cleaning-with-python
Data Preprocessing with Pandas  As part of a data analysis project, I utilized pandas, a powerful data manipulation library in Python, to preprocess and clean a dataset.

I performed the following tasks:

Removing Duplicate Rows: I applied the drop_duplicates() method directly to the DataFrame to remove duplicate rows.

Handling Index: I used the index attribute of the DataFrame along with the drop_duplicates() method to obtain a list of unique index values. This allowed me to identify and preserve unique rows based on their index values.

Data Cleaning: For further data cleaning, I employed string manipulation techniques. For instance, I used methods like str.strip() to remove leading and trailing whitespaces from string columns, ensuring consistency and improving data quality.

Converting Text to Lowercase: Using the str.lower() method, I converted text data in a specific column to lowercase. 

This operation standardized text entries, making subsequent analysis more robust and reducing the risk of duplication due to case discrepancies.

By effectively preprocessing the data using pandas, I ensured that the dataset was ready for subsequent analysis, enabling accurate insights and informed decision-making.
