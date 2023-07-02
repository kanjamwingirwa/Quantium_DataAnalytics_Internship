# Quantium_DataAnalytics_Internship

This is an internship offered by Quantium on Forage. 

#### Task 1:
#### Two datasets of Quantium’s retail analytics team were provided. The Category Manager for Chips wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

#### Steps taken
#### Data Cleaning
I removed the outlier
I filled in null values with mode in one of the columns
A lot of the data was text data (ie strings) so the approach taken was a bit different. Some brand names had to be combined as they had just been misspelt eg rrd and red. I separated out the brand name, weight of product and desciption. Corrected everything into lower case and removed white spaces as well as symbols. I filtered out salsa since were only wanted chips data

#### Data Exploration
I looked at univariate and multivariate analysis. Several graphs gave me insight of each of the data sets separately. 
I merged the datasets and did further analysis on the data sets
Some insights I discovered were;
        1. Kettle was the most popular brand
        2. Mainstream Midage singles/ Couples were the most in number. 
        3. By sales budger older families brought in the most sales. 
        4. There was a dip in sales around Christmas.
        5. The 175g packet was the most popular across all customers. 

#### Testing for statistical significance
As I conducted my EDA, I discoevered a pattern and thus formed a hypothesis. I tested the hypothesis for statistical significance.
Perform an independent t-test between mainstream vs premium and budget midage
and young singles and couples
The difference was found to be statisticlly significant thus we delved further into this market segment.

### Market Basket Analysis
With the particular market segment I had zoomed in on (Mainstream Young Singles/Couples) I decided to carry out market analysis to see how they shop.

#### Conclusions/Recommendations
Sales have mainly been due to Budget - older families, Mainstream - young singles/couples, and Mainstream- retirees shoppers.

We found that the high spend in chips for mainstream young singles/couples and retirees is due to there being more of them than other buyers. Mainstream, midage and young singles and couples are also more likely to pay more per packet of chips. This is indicative of impulse buying behaviour. They also have more to spend but may not be as choosy as their premium customers

We’ve also found that Mainstream young singles and couples are 23% more likely to purchase Tyrrells chips compared to the rest of the population. Perhaps these tyrell chips can be placed somewhere where they are more visible to this group of customers.

Apriori and association rule analysis for brand and packet size did not provide any relationship between different products.

Finally, Affinity analysis of mainstream young singles/couples suggests that they prefer the Brand "Tyrrells" and packet size of "270g"
