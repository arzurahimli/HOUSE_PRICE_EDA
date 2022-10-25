# HOUSE PRICE EXPLORATORY DATA ANALYSIS
Dataset in this analysis contains 4600 rows and 19 columns about house. 

### DATA CLEANING AND MANIPULATION
The boxplot below reveals that there are outliers in the data which causes average price being unusually large which in turn can distort real result. 

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/outliers%20boxplot.png" width="1000" height="auto" >

In order to eliminate the effects of outliers on our findings houses with price higher than $959074.71 were omitted from dataset. In the table created based on the dataset it is obviously clear how elimination of outliers affects mean value. New dataset consists of 4213 rows adn 19 columns.

#### CORRELATION MAP
 Heat map explains the what factors have significant effect on price of the house. There are storng positive correlation between price and square foot of house, on the other hand, there is a negative corrrelation between price and age of the house. 

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/correlation_map.png" width="1000" height="auto" >

#### PRICE DISTRIBUTION
Histogram below displays the distribution of price which is almost normal distribution. It means  that prcie near the mean are more frequent in occurrence than data far from the mean

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/price_distribution.png" width="1000" height="auto" >

#### AGE DISTRIBUTION
The provided histogram illustrates the how houses were distributed based on their ages. A glance at graph reveals that average age of houses in this area is 50.

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/age_distribution.png" width="1000" height="auto" >
#### DISTRIBUTION OF THE HOUSES
This paragraphs holds information about the distribution of houses by number of floors, bedrooms, selling conditions and view of the houses. Let's analyze each of them separately.

> ##### BY SELLING CONDITION
> The given illustration depicts the number of houses by selling conditions. Most of the houses  were sold in the normal condition

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/Number%20of%20House%20by%20Selling%20Condition.png" width="1000" height="auto" >

> ##### BY VIEW
> The provided graph outlines that number of houses with poor exterior view is comparatively higher than others.

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/Number%20of%20House%20by%20View.png" width="1000" height="auto" >

>##### BY THE NUMBER OF FLOOR
>The presented bar graph depicts that most of the houses in the given area are 1 floor.

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/house_by_floor.png" width="1000" height="auto" >

>##### BY THE NUMBER OF BEDROOMS
>The given figure demonstrates the information about the number of the houses based on the number of bedrooms they contain. As can be seen houses with 3 bedrooms have higher number than other houses. 

<img src ="https://github.com/arzurahimli/HOUSE_PRICE_EDA/blob/main/DATA/GRAPHS%20and%20TABLES/house_by_bedroom.png" width="1000" height="auto" >
