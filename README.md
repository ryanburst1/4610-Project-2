# MIST 4610 Project 2
# Project-2
Dylan Vila: https://github.com/dylanvila1

Jonathan Gilbertson: https://github.com/Jonathan-Gilbertson

Robert Delorme: https://github.com/BobbyDeLorme

Ryan Burstiner: https://github.com/ryanburst1

Brett Serwin: https://github.com/brettserwin

## Description of Dataset
Our dataset contains information about the real estate market in Connecticut. The data contains information on each property’s serial number, the year it was listed, the date it was sold, the address, the assessed value, the sale amount, the sales ratio (the assessed value divided by the sale amount, the property type (residential, commercial, industrial, public utility, and vacant land), the residential type (single family home, two family home, etc.), the non-use code, the assessor remarks, the OPM remarks, and the coordinates. All of the data was stored in the CSV file as type “General” except for the date recorded column which is stored as type “Date”.

## Question 1
In the state of Connecticut, which towns have the highest volume of sales from 2001-2021? In the top 7 of those towns which town is best to invest in and when depending on the sales ratio?

## Importance 
Understanding the trends in real estate sales provides valuable insights for investors looking to buy property. Identifying the top 7 towns in Connecticut with the highest number of sales narrows down the focus to areas that have consistent real estate activity. This information is immensely important for investors, since property in areas with low real estate activity may force investors to hold unwanted property due to a lack of buyers. Analyzing the sales ratios within these top towns becomes just as important, as it allows investors to understand which of the popular towns offers the most favorable investment climate. The lower the sales ratio the larger the difference between the assessed value and the actual sale price. Ideally, investors want to buy during the highest average sales ratio, allowing them to buy close to the assessed value. Then sell at the lowest average sales ratio allowing them to sell well above the assessed value. Using sales ratio investors can determine the best time to invest and make strategic decisions. 

## Graph 1
<img width="566" alt="Screen Shot 2023-12-06 at 5 16 59 PM" src="https://github.com/ryanburst1/4610-Project-2/assets/148258130/fd417055-73a9-4722-ada8-abb75853b606">


Our first graph illustrates the count of properties sold in Connecticut by town and filtered to only show the 7 towns with the largest number of sales from 2001-2021. We noticed that the top 2 towns, Waterbury and Bridgeport, have noticeably larger amounts of sales than the next 5 towns, which sit around 10,000 sales.

## Graph 2
<img width="571" alt="Screen Shot 2023-12-06 at 5 17 24 PM" src="https://github.com/ryanburst1/4610-Project-2/assets/148258130/c4005220-e567-4355-904f-d9d40fd84527">


In our second graph, we look at the average sales ratio for each town by month. The results show similar trends between Fairfield, Stamford, Norwalk, and West Hartford. The town with the most volatile sales ratio throughout the year is Bridgeport with the maximum average sales ratio peaking at 2.788 in October and a low of 1.130 in September. The town that has the most steady sales ratio and the lowest average sales ratio is West Hartford peaking at under 1.0 in the month of May and at its lowest month of July with an average sales ratio of under 0.5. Visualizing to us that West Hartford will have the lowest list values, making them the cheapest at the start of bidding. This graph also lets us know that West Hartford has the most consistent list value and sale price throughout the year.

## Question 2
In the state of Connecticut, which towns have had the least and highest growing markets? Within the top 5 highest growing towns what is the average cost of each residential type?

## Importance
Our investment company looks closely at the top five fastest-growing markets as well as the bottom five slowest-growing markets when choosing investments. We wanted to see the top 5 growing markets so we can invest in high-growth places. On the other hand, it's critical to evaluate underachievers to avoid regions experiencing slow growth. Analyzing the average price of each type of residential property in these markets allows for even more refinement. We can strategically find residential properties and towns that provide the best combination for our investment goals by carefully examining affordability as well as growth trends. This also provides a visual of the volatility of the markets.

## Graph 1
<img width="595" alt="Screen Shot 2023-12-06 at 5 18 09 PM" src="https://github.com/ryanburst1/4610-Project-2/assets/148258130/efa55a2a-05c5-4285-bda6-1b7f9326a87a">


Our first graph demonstrates the percentage change in the average assessed home values in the five towns in Connecticut which saw the largest percentage increase, and also the five towns that suffered the largest percentage decrease in average value over extensive periods between 2001-2020. Through our analysis, we were able to conclude that the five towns with the largest percentage increase in average assessed home value were: Sherman, Killingly, Goshen, Warren, and Suffield. We also were able to see the 5 lowest which were Durham, Easton, Middlebury, Middlefield, and Somers.

## Graph 2
<img width="555" alt="Screen Shot 2023-12-06 at 5 19 01 PM" src="https://github.com/ryanburst1/4610-Project-2/assets/148258130/8b942ec6-9654-4c67-9712-d9cbe20c8aa3">


Our second graph illustrates the average assessed value over periods from 2001-2020 of the five towns that we observed had the highest percentage increase in average assessed home value, broken down into the four residential types. For example, in terms of single-family homes, the towns that showed the highest yearly volatility over the past 20 years were Warren and Sherman. Having this information, we are more likely to invest in single-family homes in towns such as Killingly and Suffield, which have shown steadier growth in the market.

## The Manipulations Applied to The Dataset As Part of The Analysis
Many manipulations were necessary to prepare our data set for use in Tableau. To start, we wanted to only focus on residential properties that already had structures built on them, thus excluding all properties with “Property Type” of commercial, industrial, public utility, and vacant land. Next, we deleted the columns of the serial number, address, non-use code, assessor remarks, OPM remarks, and location as they were not relevant to our analysis and kept causing Excel to crash due to the massive amount of data in this set. Once we stripped the data down to only the information necessary for our analysis, we used a combination of MAXIFS and MINIFS to determine the year of the earliest and most recent sales for each town. Once we had that information, we used it to find the average assessed value for each town in the earliest and most recent years it had a sale recorded. Once we had these averages, we used them to find the percent change for each town, focusing on the towns with the five greatest percent increases and five greatest percent decreases in average assessed value. We performed this analysis to identify the 10 towns where there had been the greatest changes over the period. We were interested in finding out this list of towns because they hold the most opportunity for investors to see lucrative returns. In the towns with fast-growing markets where there has been a lot of growth in average assessed value, investors are positioned to take advantage of the momentum of the market and possibly see more returns on short-term investments. On the contrary, places that have seen a large percent decrease in average assessed value may be undervalued and provide the opportunity to invest in a property at a discount which primes an investor to make considerable returns over a long-term holding period while waiting for that market to rebound. Overall, through this analysis, we were able to better narrow our scope and identify towns with high potential to generate returns through real estate investment. 

##Tableau Packaged Workbook
The packaged workbook containing the visuals above is attached to the repository.


