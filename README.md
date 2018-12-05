## Case Studies in Pandas (Finance focus)

November 2018

Going into generating a report on The Great Recession

### **Looking Back: A decade after the Great Recession?**

A general slowdown in economic activity, a downturn in the business  cycle, a reduction in the amount of goods and services produced and  sold—these are all characteristics of a recession.

  ![](assets/recession.jpeg)   

According to the [National Bureau of Economic Research](http://www.nber.org/) (the official arbiter of  U.S. recessions), there were [10 recessions](http://www.nber.org/cycles/)  between 1948 and 2018.  The most recent recession began in December  2007 and ended in June 2009, though many of the statistics that describe  the U.S. economy have yet to return to their pre-recession values. 

#### Chapter 1 - Where are all the data? A review of previous pandas courses.

- Lesson 1.1 - Getting all the data in the same places
  - A learning objective: Importing several data frames into one platform using function `pd.read_csv`, `pd.read_excel`
- Lesson 1.2 - Manipulating multiple data frames
  - A learning objective: Merging several data frames based on different conditions (`merge`, `pd.concat`, `join`)
- Lesson 1.3 - EDA (statistical and graphical methods)
  - A learning objective: Getting some basic statistical information from the importing data (indexing, apply)

#### Chapter 2 - How bad was The Great Recession?

Showing the students to creates different types of plot showing how bad was the Great Recession.  

- Lesson 2.1 - Unemployment rates among States 
  - A learning objective: Learning to use matplotlib to plot unemployment rate on the US map.
- Lesson 2.2 - Unemployment rates around the world
  - A learning objective: Practicing `filter` function to compare US unemployment rates with 3 other countries of student's interest.
- Lesson 2.3 - Consequences on different industries
  - A learning objective: Learning to create a grouped bar chart to compare different industries in different periods (`groupby`, pandas plot)
- Lesson 2.4 - Establishment Births and Deaths
  - A learning objective: Creating area plot represent birth and death rate before and after the recession.

#### Chapter 3 - The laser focus - Creating your own version of this analysis

Thinking of narrowing the story but don't know what to do. Thinking of showing the student how to calculate some statistical number/ financial criteria/ doing data engineering.

- Lesson 3.1 -  Looking at a particular company stock price in the dataset
  - A learning objective: Learn how to work with time series dataset and create a stock price chart.
- Lesson 3.2 - Creating a function to calculate Sharpe ratio for the chosen company.
  - A learning objective: Learn/ review how to construct function 
- Lesson 3.3 -  Generalize the use of function for several company
  - A learning objective: Use the function created above to other company using `.apply` for the whole data frame
- Lesson 3.4 - Other metrics
  - A learning objective: Creating another function to calculate other risk adjusted return metrics with less hand holding code

#### Chapter 4 - The consequences and how it changes America's economy

Thinking of teach students to maybe automate the whole process by creating pipeline? Or maybe predicting/ creating alert of recession?

- Lesson 4.1 - 
  - A learning objective: 
- Lesson 4.2 - 
  - A learning objective: 
- Lesson 4.3 - Putting it All Together 
  - A learning objective: 

References:

[Report from The Washington Post](https://www.washingtonpost.com/graphics/2018/business/great-recession-10-years-out/?noredirect=on&utm_term=.28f090cdbafd)

[Report from Bureau of Labour Statistic](https://www.bls.gov/spotlight/2012/recession)

[Plot matplotlib with basemap](https://stackoverflow.com/questions/39742305/how-to-use-basemap-python-to-plot-us-with-50-states)