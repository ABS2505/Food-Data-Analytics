# Food-Data-Analytics
Project Overview

This project analyzes the Zomato restaurant dataset to understand customer preferences, restaurant performance, and identify operational bottlenecks.

Since the dataset does not include delivery time or order timestamps, bottleneck detection is performed using ratings, votes, cost, and location-based analysis.

Objectives

- Analyze restaurant demand and performance
- Identify low-performing restaurants (bottlenecks)
- Perform location-wise analysis
- Study impact of cost, votes, and online ordering
- Visualize trends using charts


 Dataset

- Source: Zomato Restaurants Dataset (India)
- Features include:
  - Restaurant Name
  - Location
  - Rating
  - Votes
  - Cost for two
  - Online order availability
  - Cuisine types


 Tools & Technologies

- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook



 Data Preprocessing

- Cleaned "rate" column (removed '/5', handled 'NEW', '-')
- Converted votes and cost columns into numeric format
- Handled missing values

Analysis Performed

Bottleneck Detection

- Identified restaurants with low ratings (< 3.5)
- Found high-vote but low-rated restaurants
- Detected locations with poor average ratings

 Exploratory Analysis

- Location-wise restaurant distribution
- Cost vs rating analysis
- Votes vs rating relationship
- Online order impact on ratings

Visualizations

- Bar charts for location-based analysis
- Scatter plots for votes vs rating and cost vs rating
- Comparative charts for online ordering

Key Insights

- Certain locations have a higher concentration of low-rated restaurants
- High votes with low ratings indicate serious service issues
- Some expensive restaurants provide poor value for money
- Online ordering services may impact customer satisfaction


Limitations

- No delivery time or order timestamp available
- Delay analysis could not be performed directly
- Bottlenecks inferred using rating-based indicators

Conclusion

The analysis successfully identifies underperforming restaurants and locations. These insights can help improve customer satisfaction and operational efficiency.
