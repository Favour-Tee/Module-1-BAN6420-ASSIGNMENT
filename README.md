# Module-1-BAN6420-ASSIGNMENT

Highridge Construction Company Payment Slips

Overview
This project involves generating and managing weekly payment slips for 400 workers of the Highridge Construction Company. 
The script dynamically creates a dataset, assigns employee levels based on salary and gender, and includes exception handling to ensure robust execution.
Features
Dynamic Worker Generation:

Creates a dataset for 400 workers with unique IDs, random salaries, and genders.
Conditional Logic for Level Assignment:

Employees with salaries between $10,000 and $20,000 are assigned "A1".
Female employees with salaries between $7,500 and $30,000 are assigned "A5-F".
Error Handling:

Utilizes tryCatch() to handle potential errors during worker record creation.
Efficient Data Handling:

Built using the dplyr package for streamlined data manipulation.
Prerequisites

R (Version 4.0 or higher)
RStudio (Optional, for an enhanced development environment)

Required packages:
dplyr (Install using install.packages("dplyr"))

Installation
Install R:
Download and install R from CRAN.

Install RStudio (Optional):
Download and install RStudio from RStudio.

Install Required Package:
Open R or RStudio and run:

install.packages("dplyr")

Usage Instructions
Clone or Download the Script:
Save the R script file (highridge_payments.R) to your computer.

Run the Script:
Open the script in RStudio or an R terminal and execute it. The following steps are included in the script:

Worker dataset generation.
Conditional employee level assignment.
Error handling for robust execution.
View the Data:

Use print(workers) to display the dataset in the console.
Use View(workers) to open the dataset in a tab for inspection.

Modify Output Limits (if necessary):
If output is truncated, adjust the print limit:

options(max.print = 10000) 

   id  salary gender level
1   1  18567   Male    A1
2   2  25341 Female  A5-F
3   3   9468   Male Unassigned
4   4  11234 Female    A1 ...

License
This project is open-source and can be modified or distributed for educational purposes.
