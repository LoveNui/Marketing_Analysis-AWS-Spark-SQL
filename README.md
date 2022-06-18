# Amazon_Vine_Analysis

## Overview

After the success of the SellBy project, our group will be running an analysis Amazon reviews written by members of the paid Amazon Vine program. We analyzed the TV review dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We then used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.

Below you will see dataframes we used to analyze the TV review data.

### Review Data
![Review Data](https://github.com/rivas-j/Amazon_Vine_Analysis/blob/a87cdd5025931974fa234c9f6b5942414ab36818/Resources/review_data.png)

### Review ID Table
![Review ID Table](https://github.com/rivas-j/Amazon_Vine_Analysis/blob/a87cdd5025931974fa234c9f6b5942414ab36818/Resources/review_id_table.png)

### Customer Table
![Customer Table](https://github.com/rivas-j/Amazon_Vine_Analysis/blob/a87cdd5025931974fa234c9f6b5942414ab36818/Resources/cusstomer_table.png)

### Product Table
![Product Table](https://github.com/rivas-j/Amazon_Vine_Analysis/blob/a87cdd5025931974fa234c9f6b5942414ab36818/Resources/products_table.png)

### Vine Table
![Vine Table](https://github.com/rivas-j/Amazon_Vine_Analysis/blob/a87cdd5025931974fa234c9f6b5942414ab36818/Resources/vine_df.png)

## Results

- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
