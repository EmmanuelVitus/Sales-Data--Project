# SALES-DATA-PROJECT ANALYSIS
 # INTRODUCTION: 
  This repository contains an analysis of sales data collected from an open-source data analysis class with Dahel Techies. The dataset consists of 10 columns and 17,422 rows. The data preparation involved various transformations and derived columns.

# PROBLEM STATEMENT
 ## To answer key questions such as 
  - What is the minimum revenue?
  - What is the maximum revenue?
  - What is the average revenue?
  - Creating  visualizations  showing revenue by country and gender, the proportion of revenue by age band, and revenue generated by males and females in each country.
  
# DATA PREPARATION
   ## Transformation steps included:
   - Creating a new column for year and weekday from the order date, using =YEAR(F2) for year, and =(TEXT(F2,"yyyy-mm")) for weekday, where F2 represents Orderdate.
   - Merging first and last name columns to form customer names in lowercase.
   - Deriving a new column for customer age from birthdate and order date, using =YEAR(F2)-YEAR(H2) where F2 represents Orderdate and H2 represents Birthdate
   - Categorizing customers into age bands based on specified criteria,  using the =IF(Customer's age>=13, IF(Customer's age<=19, "Teenager", IF(Customer's age>=20, IF(Customer's age<=34, "Young Adult", IF(Customer's age>=35, IF(Customer's age<=49, "Adult", IF(Customer's age>=50, IF(Customer's age<=64, "Seniors", IF(Customer's age>=65, "Elderly")))))))
    

# ANALYSIS
  - The minimum revenue generated from the dataset is £3 while the Maxixmum revenue is £5,398.
  - The average revenue generated from the dataset is £1249
  - Australia generated the highest revenue, totalling £7,096,095.
  - South West followed closely, contributing a significant revenue amount.
  - The Northeast region had the least generated revenue of £4,869.

# DATA VISUALIZATION
![Revenue by country](https://github.com/EmmanuelVitus/Sales-Data--Project/assets/151396803/35ee4422-3876-4a23-9d5f-70571ff83113)

 ![Revenue by age band](https://github.com/EmmanuelVitus/Sales-Data--Project/assets/151396803/e40a2fc7-969f-4530-81b7-a2f477823c79)

  ![Revenue by male and female](https://github.com/EmmanuelVitus/Sales-Data--Project/assets/151396803/1b3b9035-c1b0-46f3-932b-37848a192df8)

  






