# Baywheels Project Query Index
###### This project was created in PgAdmin PostgresSQL. The following is a list of queries I wrote for my own reference throughtout this project. The Baywheels Bikeshare files from 4/20 to 8/22 has an updated variable names, so this project entailed a lot of renaming varibales and organizing tables so I could JOIN the files. 

## To upload files into pgAdmin:

#### 1. Use create table to make a blank table. Name this table appropriately, ex. Baywheels_tripdata_YYYY_MM

###### Query for files 4/2020 - 8/2022

CREATE TABLE BAYWHEELS_TRIPDATA_2019_12 (
	RIDE_ID text,
	BIKE_TYPE text,
	START_TIME timestamp,
	START_STATION_NAME text, 
	START_STATION_ID text, 
	END_STATION_NAME text, 
	END_STATION_ID text, 
	START_LAT numeric, 
	START_LONG numeric, 
	END_LAT numeric, 
	END_LONG numeric, 
	MEMBER_TYPE text)
	

###### Query for files 5/2019 - 3/2020

CREATE TABLE BAYWHEELS_TRIPDATA_2019_12 (
	START_TIME timestamp,
	START_STATION_ID text, 
	START_STATION_NAME text, 
	START_LAT numeric, 
	START_LONG numeric, 
	END_STATION_ID text, 
	END_STATION_NAME text, 
	END_LAT numeric, 
	END_LONG numeric, 
	BIKE_ID numeric, 
	MEMBER_TYPE text)
	
######	- Left out Duration (s), and bike_share_for_all columns that are present in some, but not all of these files 

#### 2. Open .csv files and check for abnormalities before uploading data. Then in pgAdmin import data into appropriate table name
