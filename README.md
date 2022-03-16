# Texas-Counties
To assist college grads in deciding where to live and work in Texas, my team and I created a Python visualization using Altair to describe economic tenets of Texas counties

The main part is an interactive Texas Map that has Texas sectioned off by counties where a user can hover over a county on the map and learn of that county's 2019 housing price growth rate - personal income growth rate to highlight how well off residents are on average in different counties in 2019. 

Once a user clicks on a specific county on the map, the other parts of the visualization activate to show time series data on different economic tenets of living in Texas from 2000 to 2020. The different aspects of the visualization are below: 

1. A line chart that shows the trend of housing price growth - personal income growth from 2000 to 2020. Clicking multiple counties on the maps activates multiple line graphs so you can compare these trends between different counties. 
2. A line chart that shows the trend of unemployment rate from 2000 to 2020. Similar to the housing price vs personal income growth line chart, you can compare the trends between different selected counties in order to decide where to work after college.
3. A scatterplot that shows the distribution of all the counties in Texas according to the cost of living in those counties in 2021. The data points vary in size due to the different population numbers (as of 2021). A user can hover over the different data points in order to get specific numbers on cost of living rank, name of the county, Median Home Value, and Median Rent Value (for those who rent vs. own a home)
4. Another scatterplot connected to the cost of living scatterplot that details what percent of residents rent their homes vs. own their homes. When you click on a specific county on the cost of living scatterplot, that datapoint shows up on the Rent vs. Own scatterplot so users can learn more about different county's living distributions.
5. One final line graph that shows the trend of personal income growth from 2000-2020 for selected counties versus the state average. If users are interested in salaries and how well jobs in specific counties pay versus the state average, this graph is helpful.

Overall this project involved extensive data collection, cleaning, and transformation of different publicly available datasets in order to create this complicated but beneficial visualization. I personally also learned how long that data cleaning and collection takes and how to work on a team to get a project done. Through this project I learned more about how to analyze and visualize data in Python, specifically in its web-page like visualization library Altair. 
