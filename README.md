# Sales Data Cleaning and Preprocessing

This notebook demonstrates the process of cleaning and preparing a raw sales dataset for further analysis. It focuses on handling missing values, standardizing formats, and ensuring data consistency to make the dataset ready for downstream tasks such as visualization or modeling.

## Overview

The notebook performs the following steps:

1. **Importing Libraries**  
   Essential Python libraries such as Pandas and NumPy are imported to handle data manipulation and preprocessing tasks.

2. **Loading the Dataset**  
   Reads the raw sales dataset into a Pandas DataFrame for processing.

3. **Exploring the Dataset**  
   - Displays the first few rows of the dataset.  
   - Checks the shape of the data.  
   - Identifies missing values and inconsistent entries.

4. **Handling Missing Values**  
   - Fills missing numerical values with appropriate strategies (e.g., mean or median).  
   - Fills missing categorical values using placeholders or mode.  
   - Drops irrelevant columns if necessary.

5. **Standardizing Formats**  
   - Converts dates to a uniform `dd-mm-yyyy` format.  
   - Standardizes country names (e.g., mapping “usa” to “USA”, “uk” to “UK”).  
   - Ensures string columns are consistently formatted (lowercasing or title casing as required).

6. **Generating a Cleaned Dataset**  
   - Verifies the cleaned dataset for correctness.  
   - Saves the final dataset as a new CSV file to avoid overwriting the original.

## Output

- A cleaned CSV file ready for analysis.
- A reproducible notebook showing all transformation steps.
