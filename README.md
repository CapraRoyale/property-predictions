# Property Predictions

Predictive modeling of Real Estate using Machine Learning and dimensionality reduction

## Data Analysis on Redfin sales data to explore predictive possibilities

### By [Sravani](https://github.com/sravani61), [Lee](https://github.com/hageslel), [Roman](https://github.com/rrivera94) [Siege](https://github.com/CapraRoyale)

### Data Source and Objective

Using monthly sales data from [RedFin](https://www.redfin.com/news/data-center/) spanning 2012-2020, we wanted to explore relationships between the Median Sales Prices of homes in any given neighborhood of Seattle, and meta-data about related sales. This included the number of new sales on the market, the total inventory of homes, and the length of time the average home was for sale, among other measures.

### Discoveries

The bulk of our research was done in Data Exploration by running a variety of models to find correlations and determine if there was any meaningful predicatability. As we discovered, there was very little correlation between the majority of measures, and the few that existed were self-referential.

![Correlation Map](/Neighborhood_models_Images/correlation.png)

### Conclusions

Given the dataset, no real meanignful connections can be made, however we posit that a few extra datapoints may produce more meaningful relationships. For example, the average salary of neighborhood residents would likely result in stronger correlations for Median Sales Price of a home in any given neighborhood.
In addition, fundamental details about houses in each neighborhood would be helpful to predict Median Sales Price, details such as room count, number of floors, floor area, year built, etc.
