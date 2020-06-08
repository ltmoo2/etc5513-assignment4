# Analysisi for Life expectancy

Life expectancy is an important indicator of population health. Exploring life expectancy can provide valuable insights for each country to formulate corresponding policies to improve the health level and life expectancy.
This project focuses on the following four research questions:
- The differences of life expectancy for sex.
- The differences of life expectancy at birth and at age 60 years.
- The relationship between life expectancy and GDP
- The relationship between life expectancy and health expenditure.



# Data

1.life_expectancy.csv
+------------------------------------------------------------------+
|     key                                                 value    |
+------------------------------------------------------------------+    
|   <chr>                                               | <chr>    |
| 1 X1_Country                                          |character |
| 2 X2_Year                                             |character |
| 3 Life expectancy at birth (years)_Both sexes         |character |
| 4 Life expectancy at birth (years)_1_Male             |character |
| 5 Life expectancy at birth (years)_2_Female           |character |
| 6 Life expectancy at age 60 (years)_Both sexes        |character |
| 7 Life expectancy at age 60 (years)_1_Male            |character |
| 8 Life expectancy at age 60 (years)_2_Female          |character |
|9 Healthy life expectancy (HALE) at birth (years)_Bo~  |character |
|10 Healthy life expectancy (HALE) at birth (years)_1_~ |character |
|11 Healthy life expectancy (HALE) at birth (years)_2_~ |character |
|12 Healthy life expectancy (HALE) at age 60 (years)_B~ |character |
|13 Healthy life expectancy (HALE) at age 60 (years)_1~ |character |
|14 Healthy life expectancy (HALE) at age 60 (years)_2~ |character |
+------------------------------------------------------------------+   

2.health_expendiiture.csv
+----------------------------------------------------+
|       key                                 value    |
+----------------------------------------------------+
|       <chr>                              |<chr>    |
|     1 Country                            |character|
|     2 Year                               |character|
|     3 Health expenditure per capita(US$) |double   |
+----------------------------------------------------+

3.gdp_data.csv
+---------------------------------+
|key                 value        |
+---------------------------------+
|   <chr>          |<chr>         |
| 1 Country Name   |character     | 
| 2 Country Code   |character     |
| 3 Indicator Name |character     |
| 4 Indicator Code |character     |
| 5 Year           |double        |
| 6 GDP            |double        |
+---------------------------------+ 

4.Population_data.csv
+---------------------------------+
|key                 value        |
+---------------------------------+
|   <chr>          |<chr>         |
| 1 Country Name   |character     | 
| 2 Country Code   |character     |
| 3 Indicator Name |character     |
| 4 Indicator Code |character     |
| 5 Year           |double        |
| 6 Populaton      |double        |
+---------------------------------+ 

5.Continent data
+---------------------------------+
|    key              value       |
+---------------------------------+
|   <chr>          |<chr>         |
| 1 Continent      |character     | 
| 2 Country        |character     |
+---------------------------------+ 
(Link:https://raw.githubusercontent.com/dbouquin/IS_608/master/NanosatDB_munging/Countries-Continents.csv)



# Packages

Please download all the packages required for this project from Renv for reproducibility.


# Licence

CC0 1.0 Universal.
