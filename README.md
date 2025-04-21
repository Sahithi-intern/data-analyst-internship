Student Dataset Cleaning

 *Description*
->This project involves cleaning a raw student dataset using Google Colab. The cleaning process includes handling missing values, removing duplicates, standardizing text values, formatting date columns, and fixing incorrect data types.



-> Data Cleaning Steps

- **Handled Missing Values**: Identified and filled or removed rows with missing data using `.isnull()`.
- **Removed Duplicates**: Used `.drop_duplicates()` to eliminate duplicate rows.
- **Standardized Text Columns**: Corrected inconsistent text values like gender and country names.
- **Date Formatting**: Converted all date fields to a consistent format (`dd-mm-yyyy`).
- **Column Renaming**: Renamed column headers to lowercase with underscores (e.g., `student_name`, `enrollment_date`).
- **Data Type Conversion**: Ensured appropriate data types (e.g., age as integer, date as datetime).


-> How to Use

1. Clone or download the repository.
2. Use the file `cleaned_student_dataset.csv` to access the cleaned data.
3. Open and run the `student_data_cleaning.ipynb` (Google Colab notebook) to see or reproduce the cleaning process step-by-step.



->Files in this Repository

- `cleaned_student_dataset.csv` – Final cleaned dataset.
- `student_data_cleaning.ipynb` – Google Colab notebook with the data cleaning code and explanation.


->Tools Used
- Python
- Pandas
- Google Colab
- CSV Handling

