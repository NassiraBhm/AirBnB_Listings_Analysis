# Airbnb Listings Analysis:
As Airbnb gained popularity, many cities introduced regulations to control short-term rentals. In this project, we analyze Airbnb listings with a focus on pricing trends and host activity in Paris, aiming to assess whether regulations adopted in 2015 had a measurable impact on the market.

Using Python and Pandas, we began by loading and exploring the dataset. Initial steps included inspecting the structure of the data with .head(), checking column names, and converting the host_since column into a proper datetime format. We then filtered the dataset to retain only listings located in Paris, focusing on relevant columns such as host_since, neighborhood, city, accommodates, and price.

We performed basic descriptive analysis (.describe()) and checked for missing values. Next, we grouped listings by neighborhood to calculate the average price per neighborhood, identifying Elysées as the area with the highest average price. We then analyzed pricing patterns within Elysée by comparing average prices across different accommodation capacities (accommodates).

To evaluate the impact of the 2015 regulations, we examined yearly trends in:

Average listing prices

Number of new hosts joining the platform

This involved aggregating data by year and calculating both metrics accordingly. To better visualize insights, we created several plots:

Bar chart of average prices by neighborhood in Paris

Bar chart of average price by accommodation capacity

Dual line chart showing:

The number of new hosts per year

The average listing price per year

The results clearly indicate a regulatory impact in 2015:
→ The number of new hosts dropped significantly after 2015
→ Average prices increased, suggesting a tightening supply in the Paris Airbnb market

