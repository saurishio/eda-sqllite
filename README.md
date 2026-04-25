Project — SpaceX SQL Exploratory Data Analysis (EDA)
SQL Notebook has been used inside a Jupyter Notebook to explore and analyze SpaceX launch data stored in a SQLite database.

Setup & Data Loading:

Installs sqlalchemy, ipython-sql, and prettytable
Downloads the SpaceX CSV dataset directly from IBM's cloud storage
Loads it into a SQLite database (my_data1.db) as a table called SPACEXTABLE
Removes blank rows by filtering where Date is not null


10 SQL Tasks performed:

1. Unique launch site names
2. 5 records where launch site starts with 'CCA'
3. Total payload mass carried by NASA (CRS) boosters
4. Average payload mass for booster version F9 v1.1
5. Date of first successful ground pad landing
6. Boosters with drone ship success and payload between 4000–6000 kg
7. Count of successful vs failed mission outcomes
8. Booster versions that carried the maximum payload mass
9. 2015 drone ship failures with month, booster, and launch site
10. Ranked landing outcomes between June 2010 and March 2017


