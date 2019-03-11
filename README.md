## NBA Age ETL
Data integration is an important part of working with data. In this project, we extracted NBA player of the week data, and made some transformations using Pandas. Then, We joined it with NBA player career stats, before continuing our transformations. Finally, we loaded the cleaned and structured data into a MySQL database.

### Extract 
Extract data from:
* [NBA Player of Week](Resources/NBA_player_of_the_week.csv)
* [NBA Players - Basic Season Stats](Resources/NBA%20Players%20-%20Basic%20Season%20Stats%20%281950-2017%29.csv)

### Transfrom
* Combine datasets and include only those players that have won Player of the Week in their careers.
* Drop unnecessary columns
* calculate z-scores for players in dataframe

### Load 
Load cleaned and structured data into a MySQL database

