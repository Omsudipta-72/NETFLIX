# NETFLIX
DATA CLEANING
1.For identifying and handling missing values using filters in Excel 

Use =ISBLANK(A2) to check for blanks.
Use filters to find and handle missing cells.
Use Find & Select > Go To Special > Blanks to select all blank cells.
Use Clear, Delete, or fill with a value as needed.

2. For removing duplicate rows using Excel’s “Remove Duplicates”.

Select your data.
Go to Data > Remove Duplicates.
Choose the columns to check for duplication.

3.For standardize text values like gender, country names, etc.

Use =LOWER(TRIM(A2)) to normalize text.
Use Find & Replace or =IF() logic for mapping inconsistent values.

4.For convert date formats to a consistent type (e.g., dd-mm-yyyy).

Use Text to Columns with Date format.
Format cells: Right-click > Format Cells > Date > Choose format dd-mm-yyyy.

5.For rename column headers to be clean and uniform.

Manually rename headers to lowercase and remove spaces.
Use =LOWER(SUBSTITUTE(A1, " ", "_")) if automating in formulas.

6.For check and fix data types.

Use =INT(A2) to convert text to number.
Use Text to Columns or DATEVALUE() to convert dates.
Check data types using formatting or formulas like =ISTEXT() or =ISNUMBER().

Conclusion:-
Cleaning your data is a critical step in any data analysis workflow. Whether you're using Python or Excel, following these steps ensures your dataset is consistent, reliable, and ready for insights.
