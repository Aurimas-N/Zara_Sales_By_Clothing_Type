# Exploration:
* Check for missing values: First we use `=COUNTBLANK(A1:P253)` formula how much of missing values we have - result 3, on next step we use conditional formating to find them and highlight.
* Check for dublicate records:`Product ID` is our primary key - In empty column i use `=COUNTIF(A$2:A$253, A2) > 1` and drag it down to see if there is any dublicates - all rows are `FALSE`.
* Check data types to ensure that numerical values are stored as numbers and categorical values as text: for columns with numbers `=ISNUMBER(A2)` , for columns with text i use `=ISTEXT(A2)`. (A2 is just example i use different column naming for each check)
* Primary key has to have 6 digits number - formula `=LEN(A2)=6` and drag down shows if all rows are TRUE, meaning its 6 digits.
* Check for outliers - Calculate minimum, and maximum values for numerical columns: `=MAX(F2:F253)`, `=min(F2:F253)` etc.

# Cleaning:
* Checking if missing values can be filled - It was found that one row is missing two values, so it was decided to be removed, because there was not enough information to fill them, another missing value was filled by finding missing information in website.
* 
