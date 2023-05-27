# Introduction to the Real Estate Database

The Real Estate Database contains information about real estate lands in Riyadh for the first Quarter in 2022, including their prices per meter, sizes, names of the neighborhoods, and the total price. The dataset was sourced from the Ministry of Justice.

## Exploratory Data Analysis (EDA)

In order to gain insights and understand the dataset, we performed Exploratory Data Analysis (EDA) using various steps and techniques. The following are the steps we followed:

1. **Head**: We started by examining the first few records in the dataset using the `head` function. This allowed us to get a glimpse of the data and understand its structure.

2. **Shape**: We explored the shape of the dataset using the `shape` attribute, which provided us with the number of rows and columns in the dataset. This information helped us understand the overall size of the dataset.

3. **Info**: We used the `info` function to obtain information about the dataset, including the data types of each column, the number of non-null values, and the memory usage. This helped us understand the data types and identify any potential data inconsistencies.

4. **Describe**: By utilizing the `describe` function, we obtained summary statistics for numerical columns in the dataset. This allowed us to gain insights into the distribution, central tendency, and spread of the numerical data.

5. **Missing Values**: We examined the presence of missing values in the dataset by using the `isnull` function and summing the null values. This step helped us identify any missing data and determine the extent of data completeness.

6. **Additional EDA**: Based on the specific needs of the dataset, we conducted additional EDA steps. This could include a exploring categorical variables, and addressing outliers or data inconsistencies.

By following these EDA steps, we were able to gain a comprehensive understanding of the real estate dataset and extract valuable insights that could be used for further analysis and decision-making.

# Data Visualization

In this section, we present meaningful insights obtained through data visualization techniques. We have used various charts to analyze the real estate dataset and provide valuable insights.

## Sales Distribution over the First Quarter by Land Area

To understand the sales distribution over the first quarter based on the area of the land, we created a bar chart that compares the number of sales for three different land area categories: 'less than 300m', 'between 300m & 600m', and 'above 600m'. The chart provides a visual representation of the sales distribution, allowing us to identify any trends or variations among the land area categories.

<center>
    <img src="images/output1.png" alt="Sales Distribution by Land Area" width="600px">
</center>

## Pie Chart of Land Area Distribution

To visualize the percentage distribution of land area categories in the dataset, we created a pie chart. The chart illustrates the proportion of 'less than 300m', 'between 300m & 600m', and 'above 600m' land areas, providing an overview of the distribution.

<center>
    <img src="images/output2.png" alt="Land Area Distribution" width="400px">
</center>

## Sales Distribution by Neighbourhood for Land Area between 300m and 600m

To analyze the sales distribution within the desired land area range of 300m to 600m, we created a bar chart that breaks down the sales by neighborhood names. This chart provides insights into the distribution of sales within this specific land area range for different neighborhoods in Riyadh.

<center>
    <img src="images/output3.png" alt="Sales Distribution by Neighbourhood for Land Area between 300m and 600m" width="600px">
</center>

## Sales Distribution by Neighbourhood for Land Area above 600m

Similar to the previous analysis, we created a bar chart to examine the sales distribution by neighborhood for land areas above 600m. This chart allows us to compare the sales performance of different neighborhoods within this land area range.

<center>
    <img src="images/output4.png" alt="Sales Distribution by Neighbourhood for Land Area above 600m" width="600px">
</center>

## Average Price per Meter in Neighbourhoods (Above 600)

To determine the average price per meter in different neighborhoods for land areas above 600m, we created a bar chart. This chart provides insights into the pricing trends and helps identify neighborhoods with higher or lower average prices per meter.

<center>
    <img src="images/output6.png" alt="Average Price per Meter in Neighbourhoods (Above 600)" width="600px">
</center>

## Average Price per Meter in Neighbourhoods (Between 300 and 600)

To analyze the average price per meter in different neighborhoods for land areas between 300 and 600, we created a bar chart. This chart allows us to compare the pricing trends among neighborhoods within this land area range.

<center>
    <img src="images/output7.png" alt="Average Price per Meter in Neighbourhoods (Between 300 and 600)" width="600px">
</center>

## Additional Charts and Insights

In addition to the specific questions mentioned above, we have generated several other charts to drive meaningful insights from the real