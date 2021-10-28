# CIS129 Introduction to Programming Logic
## Project 1: Software Sales
A software company sells a package that retails for $99. Quantity discounts are given according to the following table:<br>

|Quantity|Discount|
|-|-|
|10-19|20%|
|20-49|30%|
|50-99|40%|
|100+|50%|

Design a program that asks the user to enter the number of packages purchased.<br>
The program should then display the amount of the discount (if any) and the total amount of the purchase after the discount.<br>

## Project 2: Ankh-Morpork Census
The city of Ankh-Morpork held a special census to collect data on its residents. The file containing the results of the census is structured as follows:

|FIELD DESCRIPTION|DATA TYPE|VALID VALUES|
|-|-|-|
|Age|Numeric|Greater than 0|
|Gender|Character|M, m, F, f|
|Marital Status|Character|M, m, S, s|
|District|Numeric|1 - 22|

The fields in each record will be separated by a comma. For example: 21, M, S, 1<br>

The city has 22 districts. The census department wants to see a listing of how many residents are in each district, and a count of residents in each of the following age groups (for all the districts combined): under 18, 18 through 30, 31 through 45, 46 through 64, and 65 or older.<br>

Example Output:

|District|Population|
|-|-|
|1|423|
|2|123|
|etc|etc|
|etc|etc|
|22|187|

|Under 18|754|
|-|-|
|18-30|622|
|31-45|852|
|46-64|543|
|65 & over|126|
