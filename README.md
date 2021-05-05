# FIFA World Cup Analysis using Python
FIFA World Cup Exploratory Data Analysis using Python

## Overview

The FIFA World Cup is a global football competition contested by the various football-playing nations of the world. It is contested every four years and is the most prestigious and important trophy in the sport of football.

## Dataset Details

The dataset contains World Cup statistics (summary, match-wise, player-wise) in three components.
1.	WorldCups - Dataset detailing season statistics along with winning summary
2.	WorldCupMatches - Dataset detailing match statistics for every season with participating teams and respective goals scored
3.	WorldCupPlayers - Dataset detailed event statistics by player for each match in every season with player information & position

Dataset Link: https://www.kaggle.com/abecklas/fifa-world-cup

## Importing, Combining, Transforming & Plotting

Datasets were downloaded from the source, unzipped and then imported as dataframes from their component csv files in the python environment. The function <i>read_csv</i> of the pandas library was used to import the respective datasets. Basic data quality checks (structure, null-values, duplicates, summary statistics) were conducted using built-in functions of python.

Visualizations were added whenever feasible using <i>matplotlib</i> library. For other advanced functions, <i>numpy</i> library was used. Additionally, <i>datetime</i> library was used for conversion of date strings into datetime format

## Exploratory Data Analysis and Results

For the exploratory data analysis, a total of 9 questions were used to analyse the data. Following were some of the key observations:
1.	Data for years 1942 and 1946 was observed to be unavailable in the dataset
2.	Brazil won the most world cups for the duration (5), followed by Italy (4) & Germany (4), which were followed by Argentina (2) and Uruguay (2)
3.	While the highest goals were scored in the seasons of 1998 (171) and 2014 (171), the highest goals scored by the winning team were scored by Germany in 1954 (25) with the highest percentage being scored by Uruguay in the year 1930 (21.42%)
4.	Of all the seasons played, the highest scorers were from the winning team only in the years of 1962, 1978, 1982, 2002, 2010
5.	Of all the seasons, 6 world cups were won by hosting nations
6.	The highest number of yellow/red cards were issued in 2006 (391) with Portugal being issued 28 of them
7.	While 100% of the penalties were converted to goals in the initial years, the accuracy began to tumble starting 2002 (76,47%) with the lowest being in the year 2010 (60%)
8.	Number of yellow cards issued in a match were observed to be moderately correlated with the number of goals scored with Pearson’s correlation coefficient being 0.76
9.	A total of 41 own goals were scored during all seasons with Bulgaria (2) scoring the highest ever by a team in a season
10.	In the final match of 2014, a total of 6 substitutions (3 on each side) were made during the match
