# "Customer" Churn with Baltimore City Government Employee Data

## Overview
__Customer Churn__ is the percentage of a company's customers lost in a given period, which is calculated:

```
(# of customers lost in time period / # of total customers at the beginning of time period)*100%
```

This metric is most commonly used for businesses that operate on a subscription basis as a metric to assess how their customer base is shrinking or growing over time. Customer churn is important to track because: 
 - A positive customer churn rate means the business is losing customers and related revenue
 - It's expensive to get new customers (spend more money on advertising, PR, etc.)
 - If the business's success depends on a network effect (e.g. social media), this could result in damaged reputation or worse service/product for customers
 - The customer base has less company loyalty
 - There could be more competitors in the industry that may provide better or better targeted products
 - Consumer needs and wants could be shifting, which may indicate that the business might want to pivot or expand product/service offerings
 
Another way we can think of customer churn is by looking at "customers" as companys' employee bases and calculating the "customer churn" as the employee turnover rate. Understanding employee turnover rate is important for an organization for all of the same reasons stated above--it's expensive to recruit, onboard, and train new employees! Additionally, maintaining a good/strong company culture is incredibly important in employees' job satisfaction, so high turnover rates may also contribute to lower job performance and employee satisfaction.  

Here, we'll look at Baltimore City Government employee salary data from fiscal years 2011-2019 to analyze employee turnover rates for city government as a whole and by department to see if there are any departments that might strongly contribute to a potential citywide turnover rate. The raw data is availble on [Baltimore City Open Data](https://data.baltimorecity.gov/browse?category=City+Government), and the aggregated city salary data is created from [this python notebook](https://github.com/jhu-business-analytics/multiple-linear-regression-excel-example/blob/master/2019-11-13-melanieshimano-baltimore-salary-2011-2018-combined.ipynb), and available in [this repository](https://github.com/jhu-business-analytics/customer-churn-example).

## Requirements
We use pandas and numpy to parse and manipulate the salary data and we use plotly express to create data visualizations to help us visually interpret the data.
```
pandas==0.25.2
numpy==1.17.2
plotly==4.2.1
```
