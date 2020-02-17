### Data-management-project
Discover big data set ( 271,117 rows) Olympic history from Kaggle with PostgreSQL.

#### Describe the dataset & dataset source
* The dataset is from Kaggle: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results#athlete_events.csv
* It is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016. It also contains athletes' basic bio data such as age, sex, height, weight, and performance record (medal).
* This Olympic data is the result of an incredible amount of research by a group of Olympic history enthusiasts and self-proclaimed 'statistorians'. 
* The data set contains 2 files: athlete_event and noc_regions. There are 15 cloumns in file athlete_event and 3 columns in noc_regions.
* To remove issues from wrong data types, missing values and redundant values, the data was wrangled in the new data file 'region.csv': https://noc-region.s3.amazonaws.com/regions.csv

### Motivation to explore this dataset
Olympic games are leading international sporting events, they represent the highest level of worldwide competition. This dataset provides an opportunity to discover how the Olympics have evolved over time, the difference between the participation, performance of women and men, the patterns in performance of different nations,different sports.

### Algorithm
Create some transactional database tables using PostgreSQL. Build the Foreign Key - Primary Key relationship between the dimension and fact tables. Dimentional tables are built by specific category to extract all kinds of parts of category out into their own attributes.
