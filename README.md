# Baywheels Project Query Index
###### This project was created in PgAdmin PostgresSQL. The following is a list of queries I wrote for my own reference throughtout this project. The Baywheels Bikeshare files from 4/20 to 8/22 has an updated variable names, so this project entailed a lot of renaming varibales and organizing tables so I could JOIN the files. 

## To upload files into pgAdmin:

[Uploading Files](https://github.com/JuliaManfredini/Baywheels/blob/main/Query%20Index)

## Merge tables into one dataset:

## Change dataset from a view to a table:

## Update start and end station ID's into one master table:

## Find Euclidian distance (in miles):

## Find Manhattan distance (in miles):

## Find how many bikes came in and out of one station:

#### I used this to determine which docking stations had more bikes coming in than going out, meaning the station is more likely to have too many bikes docked at one time, by hour in the day. Vice versa, determine which stations are likely to not have enough bikes stationed for riders to use (if the station has many more bikes going out than coming in). A postiive number means the station has more bikes coming in than going out. A negative number means the station has more bikes going out than coming in.

#### I later used this (along with station capacity) to create an equation to identify which stations are overflowing with bikes, or barely have any, at a given time.

## Count the amount of trips taken for every route possibilty.

#### Ordered from highest to lowest to identify the most popular routes (start and end station, one way trip) taken by riders



