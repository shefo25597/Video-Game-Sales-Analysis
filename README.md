# Video-Game-Sales-Analysis

## Overview Of Project

This dataset contains a list of video games with sales greater than 100,000 copies

## About Dataset

- Rank:  Ranking of overall sales
- Name: The games name
- Platform: Platform of the games release (i.e. PC,PS4, etc.)
- Year: Year of the game's release
- Genre: Genre of the game
- Publisher: Publisher of the game
- NA_Sales: Sales in North America (in millions)
- EU_Sales: Sales in Europe (in millions)
- JP_Sales: Sales in Japan (in millions)
- Other_Sales: Sales in the rest of the world (in millions)
- Global_Sales: Total worldwide sales.

## Data Preprocessing With Python

- Check Duplicates Values
- Check Null Values
- Replace Null Values in ['Year'] Column By Median
- Replace Null Values in ['Publisher'] Column By Mode
- Convert Datatype Of Column ['Year'] To String And Remove Decimals From Values
- Create ['Decade'] Column From ['Year'] Column

## Exploratory Data Analysis With Python

- Top 10 Years That Have Highest Count Of Games
- Total Games By Decade
- Top 10 Platform That Have Highest Count Of Games
- Top 10 Publishers That Have Highest Count Of Games
- Count Of Games For Every Genre
- Global Sales Analysis
  o Top 10 [  'Name', 'Platform' ] That Have Highest Global Sales
  oTotal Global Sales For Every Decade
  oTop 10 Years That Have Highest Global Sales
  oTotal Global Sales For Every Genre
  oTop 10 Platform That Have Highest Global Sales
  oTop 10 Publisher That Have Highest Global Sales
- Europe Sales
  oTop 10 [  'Name', 'Platform' ] That Have Highest EU Sales
  oTotal EU Sales For Every Decade
  oTop 10 Years That Have Highest EU Sales
  oTotal EU Sales For Every Genre
  oTop 10 Platform That Have Highest EU Sales
  oTop 10 Publisher That Have Highest EU Sales
- North America Sales
  oTop 10 [  'Name', 'Platform' ] That Have Highest NA Sales
  oTotal NA Sales For Every Decade
  oTop 10 Years That Have Highest NA Sales
  oTotal NA Sales For Every Genre
  oTop 10 Platform That Have Highest NA Sales
  oTop 10 Publisher That Have Highest NA Sales
- Japan Sales
  oTop 10 [  'Name', 'Platform' ] That Have Highest JP Sales
  oTotal JP Sales For Every Decade
  oTop 10 Years That Have Highest JP Sales
  oTotal JP Sales For Every Genre
  oTop 10 Platform That Have Highest JP Sales
  oTop 10 Publisher That Have Highest JP Sales


## Data Visualization With Power BI

- Four Pages for Dataset Visualization
  oFirst Page For Global Sales
  oSecond Page For EU Sales
  oThird Page For NA Sales
  oLast Page For JP Sales
- Measures For: 
  oCount OF Games 
  oDistinct Count Of Platforms 
  oDistinct Count Of Publishers 
  oTotal Of Global Sales 
  oTotal Of EU Sales
  oTotal Of NA Sales
  oTotal Of JP Sales
- Dashboard in Every Page Has:
  oName Of Type Of Analysis
  oPage Navigator For Every Page
  oSlicers For:
    - Platforms
    - Publishers
  oCount OF Games # Card
  oDistinct Count Of Platforms # Card
  oDistinct Count Of Publishers # Card
  oTotal Of Sales # Card
  oTotal Sales By Genre # Column Chart
  oTop 5 Platforms That Have Highest Sales # Bar Cart
  oTop 5 Publishers That Have Highest Sales # Bar Chart
  oTotal Sales By Years # Line Chart
