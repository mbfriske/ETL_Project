# ETL
###### Ever wonder if Starbucks drives happiness? 
----------------
#### Extract:
Datasets were foudn on Kaggle.com to extract our primary Datasets. 
1.	https://www.kaggle.com/unsdsn/world-happiness#2017.csv
2.	https://www.kaggle.com/starbucks/store-locations
3.	https://www.kaggle.com/koki25ando/country-code

#### Transform: 
Cleaning – Used pandas to extract and clean csv files.
Formatting – Using the country code data, reformatted Starbucks Country data from abbreviations to the full country name; joined world data and Starbucks datasets.

#### Load: 
Our data was stored in a PostgreSQL database called “SuperUberDuberProject”. Within that are two tables; “happiness” and “store_directory.”
