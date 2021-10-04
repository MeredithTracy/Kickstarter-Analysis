# Kickstarter-Analysis
Perform an analysis using the [Kickstarter Dataset](https://github.com/MeredithTracy/Kickstarter-Analysis/blob/main/Kickstarter_Challenge%20-%20Clean.xlsx) to assist Louise in comparing how her kickstarter for her play, Fever, fared compared to others. Louise mainly wants to focus on the funding goals and launch dates. 

## Process
The [Kickstarter Dataset](https://github.com/MeredithTracy/Kickstarter-Analysis/blob/main/Kickstarter_Challenge%20-%20Clean.xlsx) is large and has a lot of variety in the data provided so filtering and sorting the data was critical to finding the answers. Using pivot tables and COUNTIFS functions, I was able to narrow the data. One of the challenges I faced working with this data was the columns that existed in the original set. They were not the most efficient way to sort through the data. I was able to split and create new columns for most of these challenges but to get to the “Outcomes Based on Goals” chart, seen below, I had to manually enter each formula for every section which added time to the overall analysis. 

## Analysis

### Outcomes Based on Launch Date

![Outcomes_Based_on_Launch_Data](https://github.com/MeredithTracy/Kickstarter-Analysis/blob/main/Resources/Outcomes_Based_on_Launch_Data.png)

This image shows the dataset for the chart titled Theater Outcomes Based on Launch Date


![Theater_Outcomes_vs_Launch](https://github.com/MeredithTracy/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

This image shows the chart titled Theater Outcomes Based on Launch Date


Based on this data, we can see that theater based kickstarters have the most success in the spring/ summer months beginning in May. This data includes theater kickstarters from multiple countries totaling 1,369 projects. There is also a smaller spike in October before steadily descending for the final two months of the year. 

Failed projects tend to follow a similar trajectory to the successful projects except there is not a strong spike in May. The summer numbers stay more consistent before descending again with the same spike back up in October. There is a small uptick in failed kickstarters in December unlike the successful projects. December is the month where there is the closest count between successful and failed kickstarters, counting at 37 and 35 respectively. 

Overall, there was not a lot of data for the canceled theater kickstarters. This may lend to saying that there is a trend of theater kickstarters not canceling as often but it is hard to make that conclusion without more data and more analysis. 

### Outcomes Based on Goals

![Outcomes_Based_on_Goals_Data](https://github.com/MeredithTracy/Kickstarter-Analysis/blob/main/Resources/Outcomes_Based_on_Goals_Data.png)

This image shows the dataset for the chart titled Outcomes Based on Goals


![Outcomes_vs_Goals](https://github.com/MeredithTracy/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

This image shows the chart titled Outcomes Based on Goals


For plays specifically, there is no data on canceled projects so I cannot confidently make any analysis on the trends. 

As a result of there being no canceled play kickstarters, that means our data should mirror each other. When the percentage of successful kickstarters goes up, the percentage of failed kickstarters goes down. 

Small goals start strong with an 76% success rate for goals under $1,000. There is a decline afterwards dropping down into the 55%-45% range for goals set between $5,000 - $24,999. A sharp drop down to the 20% success rate for $25,000-$29,999 range. After this, there is a jump back up to 67% from $35,000 - $44,999 before plummeting down to 0% for goals over $45,000. 

Now, what does this mean? Well it’s a bit tough to say if this is actually a trend because as you can see in the dataset above, there was only one kickstarter with a goal ranging between $45,000-$49,999. That number compared to the 534 projects with goals between $1,000 - $4,999. Based on this data we can see that there is a strong trend in goals being relatively small for play kickstarters with almost 85% of the data points being below a $10,000 goal (889 of 1,047). 

## Limitations

As stated in my analysis, there are some limitations to this data. While the dataset as a whole has a lot of variety in kickstarters, when we narrow it down to Plays and Theater productions, the data skews quite a bit so it makes it difficult to make conclusions. A larger dataset of just the theater category may be helpful for answering more questions. We had sections in our analysis where there were zero or one datapoint for an entire category which can make a chart look more extreme than it really is. 

## Further Analysis Options

I would be interested to know if there are trends based on the country the kickstarter originated in. We can see the percentages of successful/ failed/ canceled kickstarters, but are those numbers consistent between the countries or are there countries where theater kickstarters are almost always successful no matter the goal. 