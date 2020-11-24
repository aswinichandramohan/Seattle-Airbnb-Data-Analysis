# Seattle Airbnb Data Analysis

## Introduction
Airbnb is a vacation rental online marketplace. It acts as a broker receiving commissions from the host and the guests from each booking. Airbnb charges 3% from the hosts and 6% -12% depend on the type of booking from the guests. The price differs according to the city, area, neighborhood.

I have done my project in the city called Seattle which is in Washington where I live. 

## Objectives
The project aims to determine how the property listing of Airbnb looks like in Seattle.
1. Determining the average price on each property with respect to the number of listings in each neighborhood, number of reviews, number of beds, and property type (apartment, house, townhouse, condominium, etc)
2. Top 5 neighborhoods having the maximum listing price
3. Average revenue in each neighborhood
4. The average availability of top 5 neighborhoods per year
5. Number of listings based on the property type
6. Growth of Airbnb listings each year

## Dataset
Dataset is downloaded from https://www.kaggle.com/airbnb/seattle.

The dataset consists of 3 tables (listings, calendar, and reviews). The data set describes the listing activity and metrics in Seattle from 2008 to 2015. It includes information about hosts, area, reviews, rating, room type, etc.

## Analyzing the dataset
I used the PowerBI business intelligence tool to analyze the data set to gain deep insights into different Airbnb properties in Seattle.

### Determining the average price on each property

![Page1 screenshot](/images/Page1.JPG)

There are three room types available in Seattle.
* Entire home
* Private room
* Shared room

#### Finding 1: Average price on each room type:
```
Entire home: $155.84
Private room: $75.04
Shared room: $47.55
```

#### Finding 2: Top 5 neighborhood having the highest number of reviews:
```
Broadway - 8312
Belltown - 4439
Fremont - 4014
Wallingford - 3788
First Hill - 2358
```

#### Finding 3: Top 5 neighborhood having the highest number of Airbnb property listings:
```
Belltown - 7639
Central Business District - 3978
Broadway - 2188
University District - 1643
Wallingford - 1274
```

From the graphs, we can see that the average price of a listing doesn’t depend on the combination of neighborhoods and the number of reviews.

### The top 5 most expensive neighborhoods listings:

![Page2 screenshot](/images/Page2.JPG)

#### Finding 1: Top 5 neighborhoods having the highest maximum price:
```
Roosevelt - $1,000
Belltown - $999
West Queen Anne - $975 
Southeast Magnolia - $950
Westlake - $775
```

According to the map, it is very clear that the most expensive listings are in prime localities and closer to downtown. Roosevelt has the highest maximum price of $1000.

### The average revenue of listings in each neighborhood area

![Page3 screenshot](/images/Page3.JPG)

#### Finding: Top 5 Airbnb properties which can bring the highest revenue are
```
Broadway - $3,068,138
Central Business District - $1,179,249
Belltown - $1,153,043
Fremont - $966,833
First Hill - $952,564
```

Broadway fetches Airbnb’s highest revenue in Seattle.

### The Average availability of top 5 neighborhood per year

![Page4 screenshot](/images/Page4.JPG)

#### Finding 1: The top 5 neighborhood having the highest availability:
```
Holly park - 354
Roxhill - 348
High Point - 344
Highland Park - 319
Briarcliff - 315
```

From the map, it is more evident that the more properties are available to rent in the least popular neighborhoods. These are neighborhoods away from downtown and not near tourist spots.

### Number of listings based on the property type 

![Page5 screenshot](/images/Page5.JPG)

There are many property types mentioned in the datasets.
Here I am taking four popular property types:
1. Apartments
2. Condominium
3. House
4. Townhouse

#### Finding 1: Highest number of listings by neighborhood where  property type = apartment
```
Broadway - 292
Belltown - 208
First Hill - 99
Central Business District - 93
University District - 76
```

#### Finding 2: Highest number of listings by neighborhood where  property type = condominium
```
Belltown - 18
Broadway - 9
First Hill - 8
Central Business District - 6
Lower Queen Anne - 6
```

#### Finding 3: Highest number of listings by neighborhood where  property type = house
```
Wallingford - 111
Broadway - 84
Minor - 76
Fremont - 68
Greenwood - 64
```

#### Finding 4: Highest number of listings by neighborhood where  property type = townhouse
```
Mann - 10
Minor - 10
Fremont - 8
Broadway - 7
Leschi - 6
Lower Queen Anne - 6
```

From the findings, it is very clear apartments have the highest number of listings overall.

### How is the growth of Airbnb listings in each year

![Page6 screenshot](/images/Page6.JPG)

The datasets I took is from the year 2008 to 2015. 2008 is the year when Airbnb started.
From the graph, we can clearly see the increase in the number of Airbnb property listings each year. We can also see that among the different room types (entire home, private room, shared room), apartments have the highest increase in the number of listings. 

