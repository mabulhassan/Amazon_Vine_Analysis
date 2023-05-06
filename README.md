# Amazon_Vine_Analysis

## Project Overview:
This project analyzes Amazon Vine program and determines if there is any bias towards reviews that were written as part of the Vine program. 



## Purpose:

The analysis uses amazon reviews dataset and PySpark within Google colab environment to load, Extract and transform data. The data is loaded into AWS cloud based Postrgres database
and is transformed using pgAdmin tools to store different metrics and data counts.



## Results: 

### How many Vine reviews and non-Vine reviews were there?

There were a total of 613 vine reviews and 64,968 non vine reviews.
<p align="center">
  <img src="https://github.com/mabulhassan/Amazon_Vine_Analysis/blob/main/total_vine_df_count.png">
</p>
<p align="center">
  <img src="https://github.com/mabulhassan/Amazon_Vine_Analysis/blob/main/total_none_vine_df_count.png">
</p>

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were a total 222 of vine 5-star reviews and 30,543 total of none vine 5-star reviews.
<p>
  <img src="https://github.com/mabulhassan/Amazon_Vine_Analysis/blob/main/total_five_star_vine_df.png">
</p>
<p align="center">
  <img src="https://github.com/mabulhassan/Amazon_Vine_Analysis/blob/main/total_five_star_none_vine_df.png">
</p>

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The were a total of 36.2% of vine reviews that were 5 stars and 47% of non-vine reviews that were 5 stars.
  <img src="https://github.com/mabulhassan/Amazon_Vine_Analysis/blob/main/five_star_vine_percent.png">
</p>
<p align="center">
  <img src="https://github.com/mabulhassan/Amazon_Vine_Analysis/blob/main/five_none_star_vine_percent.png">
</p>



## Project Summary:
The none-vine reviews had a higher percentage of positive reviews 47% wheres the non vine reviews had only 36.2%. The total number of non vine reviews is significantly higher 64,968 compared to the total number of vine reviews that add up to only 222. The difference in count may have contributed to the positive bias and further analysis is needed to support the statment.
