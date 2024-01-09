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
  - Top 10 [  'Name', 'Platform' ] That Have Highest Global Sales
  - Total Global Sales For Every Decade
  - Top 10 Years That Have Highest Global Sales
  - Total Global Sales For Every Genre
  - Top 10 Platform That Have Highest Global Sales
  - Top 10 Publisher That Have Highest Global Sales
- Europe Sales
  - Top 10 [  'Name', 'Platform' ] That Have Highest EU Sales
  - Total EU Sales For Every Decade
  - Top 10 Years That Have Highest EU Sales
  - Total EU Sales For Every Genre
  - Top 10 Platform That Have Highest EU Sales
  - Top 10 Publisher That Have Highest EU Sales
- North America Sales
  - Top 10 [  'Name', 'Platform' ] That Have Highest NA Sales
  - Total NA Sales For Every Decade
  - Top 10 Years That Have Highest NA Sales
  - Total NA Sales For Every Genre
  - Top 10 Platform That Have Highest NA Sales
  - Top 10 Publisher That Have Highest NA Sales
- Japan Sales
  - Top 10 ['Name', 'Platform'] That Have Highest JP Sales
  - Total JP Sales For Every Decade
  - Top 10 Years That Have Highest JP Sales
  - Total JP Sales For Every Genre
  - Top 10 Platform That Have Highest JP Sales
  - Top 10 Publisher That Have Highest JP Sales


## Data Visualization With Power BI

- Four Pages for Dataset Visualization
  - First Page For Global Sales
  - Second Page For EU Sales
  - Third Page For NA Sales
  - Last Page For JP Sales
- Measures For: 
  - Count OF Games 
  - Distinct Count Of Platforms 
  - Distinct Count Of Publishers 
  - Total Of Global Sales 
  - Total Of EU Sales
  - Total Of NA Sales
  - Total Of JP Sales
- Dashboard in Every Page Has:
  - Name Of Type Of Analysis
  - Page Navigator For Every Page
  - Slicers For:
    - Platforms
    - Publishers
  - Count OF Games # Card
  - Distinct Count Of Platforms # Card
  - Distinct Count Of Publishers # Card
  - Total Of Sales # Card
  - Total Sales By Genre # Column Chart
  - Top 5 Platforms That Have Highest Sales # Bar Cart
  - Top 5 Publishers That Have Highest Sales # Bar Chart
  - Total Sales By Years # Line Chart
