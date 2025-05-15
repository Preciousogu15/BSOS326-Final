# Analyzing the Relationship Between Book Ratings and Popularity on Goodreads (2025)

## Project Overview

This project explores whether a book’s average user rating on Goodreads is related to its popularity, measured by the total number of ratings. Goodreads, as the world’s largest book review platform, influences millions of readers and shapes literary visibility through ratings and engagement. Understanding this relationship is important because it sheds light on whether highly rated books naturally attract more readers or if other factors like media exposure, author fame, or genre play a more significant role in driving popularity. Insights from this analysis can inform readers, authors, and publishers about how digital visibility and perceived quality interact in the modern book market.

## Data Collection

### Goodreads Data

* Source: Web scraped data from Goodreads’ “Best Books Ever” list
* Sample Size: 200 books representing a mix of classics, bestsellers, and cult favorites
* Variables:

  * **avg\_rating**: Average user rating (1 to 5 scale)
  * **num\_ratings**: Total number of ratings as a proxy for popularity

### Data Preparation

* Cleaned and standardized ratings and popularity counts
* Prepared data for exploratory analysis and regression modeling

## Analysis Approach

* Exploratory Data Analysis (EDA) to summarize rating distributions and popularity variance
* Identification of top-rated and most popular books to analyze extremes
* Linear Regression to examine the statistical relationship between average rating and number of ratings
* Investigation of outliers to understand discrepancies between rating and popularity

## Key Findings

* Average ratings range from 3.43 to 4.76 with a mean of 4.16, showing generally positive reception across books
* Number of ratings varies dramatically, from just over 1,200 to more than 10.9 million, indicating wide disparity in reader engagement
* Regression analysis shows no significant correlation between average rating and popularity, suggesting other factors strongly influence reader attention
* Highly rated books do not always correspond to highly popular books, highlighting the impact of external factors like author reputation and media adaptations

## Implications

* Book popularity on Goodreads is driven by complex factors beyond average rating alone
* The disparity between quality (ratings) and popularity (engagement) reveals challenges for lesser-known authors to gain visibility
* Readers should approach popularity metrics critically and explore beyond the most rated books
* Publishers and platform designers may need to improve recommendation algorithms to support diverse and quality literature

