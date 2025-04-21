**Student Dataset Cleaning**
**Description**
This project focuses on cleaning a raw student dataset using Python in Google Colab. The cleaning process involved handling missing values, removing duplicates, standardizing text entries, converting data types, and renaming columns for consistency.

**Data Cleaning Steps**
Handled Missing Values: Identified and addressed missing values using .isnull() and appropriate imputation techniques.

Removed Duplicates: Eliminated duplicate rows using .drop_duplicates().

Standardized Text Columns: Ensured consistency in text fields such as gender and country names by standardizing their formats.

Data Type Conversion: Converted columns like age to integers and dates to datetime objects for uniformity.

Date Formatting: Reformatted date fields to a consistent format (e.g., dd-mm-yyyy).

Column Renaming: Renamed columns to be lowercase with no spaces, enhancing readability and consistency.

**How to Use**
Clone the Repository:
git clone https://github.com/Sahithi-intern/data-analyst-internship.git
Access the Cleaned Data:

**Navigate to the repository directory.**

Open cleaned_student_dataset.csv to view the cleaned dataset.

**Reproduce the Cleaning Process:**

Open student_data_cleaning.ipynb in Google Colab or Jupyter Notebook.

Run the notebook cells to replicate the data cleaning steps.

**Files in this Repository**
cleaned_student_dataset.csv: The final cleaned student dataset.

student_data_cleaning.ipynb: The Python notebook detailing the data cleaning process.

->**Tools Used**
- Python
- Pandas
- Google Colab
- CSV Handling
**Conclusion:**
Learned how to clean a dataset, check for null values, and calculate basic statistics using Python. This is a fundamental step in any data analysis project.

