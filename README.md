# Module-1-BAN6420-ASSIGNMENT BY CHIGOZIE FAVOUR TOCHUKWU

Highridge Construction Company Payment Slips

Overview

This project involves generating and managing weekly payment slips for 400 workers at Highridge Construction Company. The goal is to dynamically create a dataset of workers, assign employee levels based on specific conditions, and handle errors efficiently. The implementation is provided in both Python and R.

Features
Dynamic Worker Generation

Creates a dataset of 400 workers with unique IDs, random salaries, and genders.
Conditional Logic for Level Assignment

Employees with salaries between $10,000 and $20,000 are assigned "A1".
Female employees with salaries between $7,500 and $30,000 are assigned "A5-F".
Error Handling

Exception handling is implemented in both Python and R to manage potential runtime errors.
Cross-Language Implementation

The same functionality is provided in both Python and R for flexibility.

Prerequisites

Python 3.8 or higher
Required Libraries:
pandas
Install dependencies using: pip install pandas  

R (Version 4.0 or higher)
Required Packages:
dplyr
Install dependencies using: install.packages("dplyr")  

Files Included
Python Implementation: Payment_Slip.py
R Implementation: Payment_Slip.R
README: Instructions for usage and setup.


Usage

Python
Run the Python Script:
Open a terminal and navigate to the directory containing the highridge_payments.py file.
Run the script: Payment_Slip.py  

Output:
The script generates a CSV file named worker_payments.csv containing the worker dataset.
To view the first few rows in the console, use the print statement already included in the script



R
Run the R Script:
Open the highridge_payments.R file in RStudio or an R terminal.
Run the script by clicking Run in RStudio

Output: The dataset is saved as an R data frame (workers).
Use View(workers) to inspect the data.
Modify print limits if needed: options(max.print = 10000)  


Example of Output:

Sample rows from the generated dataset:
   id  salary gender    level  
1   1  18567   Male      A1  
2   2  25341 Female    A5-F  
3   3   9468   Male Unassigned  
4   4  11234 Female      A1  


Additional Note
Both scripts use random seed values for reproducibility:

Python: random.seed(42)
R: set.seed(42)
Change the seed to generate different datasets.
Outputs can be further customized to include additional worker attributes if needed.

License
This project is open-source and can be modified or distributed for educational and non-commercial purposes.








