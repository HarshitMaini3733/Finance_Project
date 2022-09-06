# Finance_Project
Data Analysis of stock prices
In this data project we will focus on exploratory data analysis of stock prices. It is not meant to be a robust financial analysis or be taken as financial advice.

## Data

We will get stock information for the following banks:

<ul>

<li>Bank of America</li>
<li>CitiGroup</li>
<li>Goldman Sachs</li>
<li>JPMorgan Chase</li>
<li>Morgan Stanley</li>
<li>Wells Fargo</li>

</ul>

#### Head of the data :

![](Images/Plot1.png)

#### What is the max Close price for each bank's stock throughout the time period?

![](Images/Plot2.png)

#### Creating a new empty DataFrame. This dataframe will contain the returns for each bank's stock.

![](Images/Plot3.png)

#### Creating a pairplot of the returns dataframe.

![](Images/Plot4.png)

The Citygroup's stock stands out since it can be clearly seen in the visualization that its increase is minimal. More information from [Citygroup's stock crash.](https://en.wikipedia.org/wiki/Citigroup#November_2008.2C_Collapse_.26_US_Government_Intervention_.28part_of_the_Global_Financial_Crisis.29)

####Using this returns DataFrame, figure out on what dates each bank stock had the best and worst single day returns.

##### Worst Single Day return :

![](Images/Plot5.png)

You should notice that 4 of the banks share the same day for the worst drop because Barack Obama is inaugurated as the 44th and first African-American President of the United States([United States Inauguration Day 2009](https://en.wikipedia.org/wiki/Portal:Current_events/2009_January_20))

##### Best Single Day return : 

![](Images/Plot6.png)

You should have noticed that Citigroup's largest drop and biggest gain were very close to one another because [Citygroup had a stock split](https://www.citigroup.com/citi/news/2011/110321a.htm)
