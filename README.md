# Car_Sales_Analysis
To create our visualizations we used the Dataset called CarSales, which shows various stats about car model sales.

Started off by completing some data wrangling and cleaning to prepare the data to be used for analysis.

Next, found some useful descriptive stats about our data to help make decisions about what questions we would try to answer about our data.

Decide to group our data by Manufacturers and then chose to just look at Volve Models for our analysis.

We created 3 Combo Chart Visualizations comparing the Sales_in_thousands and Price_in_thousands variables for different Models of Volvo cars.
 
Using the Matplotlib, Seaborn, and Plotly libraries we generated our combo charts with Sales_in_thousands and Price_in_thousands in our y-axis and Volvo Models along the x-axis.

Comparing the visualizations we made using the 3 different libraries, we decided that using the Plotly library was our preferred method. This was the best choice for us since we enjoyed the interactiveness of the chart and the scaling the y-axis differed from the other charts. With Plotly, it changed the scale used in the y-axis to include both our variables instead of having two separate y-axises plotted at the same time.

Analysis of Results from Charts:
From the charts above, we could see that generally if the price of a car model is high then the sales will tend to be lower, although there were instances where this wasn't true. To see why that would be the case requires some further analysis.

In the future if we were to continue analysis of this data further, a few things we could do are:
  - Create visualizations for comparing Sales and Price for car Models of the other car Manufacturers
  - Test which other variables have an effect on the price variable
 
 Then we created a Waffle Chart to visualize the variable 'Vehicle_type'

Finally, we generated a word cloud to display which Manufacturers occur most in our data.
  - Manufacturer was the only variable in our data that we could use to generate a word cloud since our data contains mostly only numerical values

