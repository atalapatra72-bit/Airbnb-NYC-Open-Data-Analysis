Overview
This project investigates factors influencing Airbnb reviews in New York City using the AB_NYC_2019 dataset. The analysis explores the relationship between room types, neighborhoods, and review frequency, providing insights for hosts and prospective guests on how these variables impact engagement and review activity.

Objectives
The project addresses two main hypotheses:
1). Room Type Influence on Reviews: Does the type of room (e.g., private room, entire home/apartment) significantly affect the number of reviews per month?
2). Neighborhood Influence on Reviews: Do certain neighborhoods in New York City receive more reviews on average?
Hypothesis 1: ANOVA analysis revealed significant differences in review frequency across room types.
Hypothesis 2: Kruskal-Wallis test confirmed statistically significant differences in review frequency across neighborhoods.

Dataset
The dataset contains 48,895 observations with 16 variables, including:
Room Type: Type of accommodation (e.g., Entire home/apt, Private room, Shared room).
Neighborhood Group: Borough (e.g., Manhattan, Brooklyn, Queens).
Reviews per Month: Average monthly review count per listing.
Additional variables like price, host ID, latitude, and availability.

Key Analyses
Data Cleaning:
Handled missing values by replacing them with zeroes where logical.
Excluded non-relevant variables like name and host_name for hypothesis testing.

Statistical Tests:
Visualizations:
Boxplots for reviews by room type and neighborhood.
Scatter plots illustrating the relationship between price and reviews.
Histograms showing price distribution.
Tools and Techniques
Programming Languages: R for data processing, visualization, and statistical testing.
Libraries Used: ggplot2, dplyr, readr, car, FSA.
Statistical Methods: ANOVA, Kruskal-Wallis Test, log transformation for normalization.

Key Findings
Room Type Impact: Private rooms receive slightly more average monthly reviews compared to entire homes or shared rooms, but the majority of listings have low review counts.
Neighborhood Differences: Listings in Queens and Staten Island tend to receive more reviews per month on average, whereas Manhattan listings, despite higher all-time reviews, show lower monthly engagement.
Price-Review Relationship: Negative correlation observed—affordable listings attract more reviews, while higher-priced listings generally receive fewer reviews.

Conclusion
This analysis highlights how room types and neighborhood characteristics influence Airbnb review trends, providing actionable insights for hosts and guests to optimize listing performance and engagement.
