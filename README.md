# Web Scraper using python | Swiggy Restaurants in Delhi

### Context
Swiggy is an Indian online food ordering and delivery platform. Founded in July 2014, It is based in Bangalore and operates in 500 Indian cities as of September 2021. Swiggy is the most on-demand food delivery platform that brings food from neighborhood restaurants directly to customers' doors.

### About
I Scraped Swiggy's Top Rated Restaurants in Delhi data using Python packages like Requests, BeautifulSoup, numpy, and Pandas.
The source of data set is Swiggy's official website. Here is the link - https://www.swiggy.com/city/delhi/top-rated-collection

### Project outline
- We'll grab a list of names, and urls of top rated restaurants in Delhi on Swiggy, and put them in 'rest_page.csv'.

- Then we'll grab information like name, cuisine, location, rating, number of ratings, and price for two for each restaurant and save them in 'rest_delhi.csv'.

- The restaurants information will be stored in a csv file with format:

```
name,cuisine,location,rating,num_of_rating,price_for_two
Bhukkad's Kitchen,"North Indian, Indian","Tis Hazari, Tis Hazari",5.0,20+ ratings,₹ 199
SUSHI MACHI,Sushi,"Hauz Khas, Green Park",4.9,20+ ratings,₹ 600
```

ciao!
