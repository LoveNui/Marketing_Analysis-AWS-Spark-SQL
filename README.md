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

### Vine Reviews
![Vine Reviews](https://github.com/rivas-j/Amazon_Vine_Analysis/blob/818de7cf975e06398ce373e3b502f7954a5c2f07/Resources/vine_reviews.png)

### Unpaid Reviews
![Unpaid Reviews](https://github.com/rivas-j/Amazon_Vine_Analysis/blob/818de7cf975e06398ce373e3b502f7954a5c2f07/Resources/unpaid_reviews.png)

- In Total there were 255 Vine reviews and 22,675 unpaid reviews
- Of the 255 Vine reviews, 103 were 5 star reviews (40%)
- Of the 22,675 unpaid reviews, 10,310 were 5 star reviews (45%)

## Summary

Based on the results of our analysis comparing Vine and unpaid reviews, we did not see evidence of positivity bias within the paid reviews. A higher percentage of unpaid reviews were 5 stars. 

Here are some additional levels of analyis we are planning to apply to the current data set:
- Compare the number of 1 star reviews between Vine and Unpaid to determine any additional patterns
- Filter the Vine and Unpaid review datasets by verified purchase to add credibility to our review sample analysis
