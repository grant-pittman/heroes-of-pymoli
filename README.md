# My Analysis of Heroes of Pymoli - Pandas Challenge <!-- omit in toc -->

If you would like to see my findings, please scroll down to the findings section.

## Table of Contents <!-- omit in toc -->

- [Background](#background)
- [Reporting Steps](#reporting-steps)
  - [Player Count](#player-count)
  - [Purchasing Analysis](#purchasing-analysis)
  - [Gender Demographics)](#gender-demographics)
  - [Purchasing Analysis (By Gender)](#purchasing-analysis)
  - [Age Demographics](#age-demographics)
  - [Top Spenders](#top-spenders)
  - [Most Popular Items](#most-popular-items)
  - [Most Profitable Items](#most-profitable-items)
- [Findings](#findings)

## Background

To learn morea bout the workings of Python Pandas Library, we were given the option to choose between two challenges.
I chose the Heroes of Pymoli channelnge. In this assignment, I was given the role of Lead Analyst for an independent gaming company and assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.
My task was to generate a report that breaks down the game's purchasing data into meaningful insights. These insights could be leveraged to help the developers create more purchasable items to increase the company’s  profit. 

## Reporting Steps

My final report included the following information in tabluar form:

### Player Count

* Total Number of Players

### Purchasing Analysis

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identified the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identified the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identified the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value
  
## Findings

Here are some of my observatable trends:

1.    Most of the players are male, however females have a higher average purchase price and tend to spend more per person then men. 
2.    The leading demographic for the game is the age group 20-24 who constitute 44.8% of the total player population. Older demographics, particularly the 35-39 age group spend more on average than this leading demographic. 
3.    The most profitable item is also the most popular item. I think next time it would be interesting to analyze the relationship of profitability to item stats like strength. 


Please have a look at the DataFrames in the Jupyter Notebook for additional findings.
