# San Francisco Bay Area bike sharing Data Exploration
## by David Babalola

## Dataset

This data set includes information about individual rides made in a 
bike-sharing system covering the greater San Francisco Bay area.

The dataset has records 183,412 rides and has 16 features. 
There are 7 columns that are floats, 2 of them are ints, while 7 are object (strings).

user_type: Subscriber, Customer
member_gender: Male, Female, Other
bike_share_for_all_trip: Yes, No

The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

## Summary of Findings

In the exploration, I found that there was a strong relationship between the
price of a diamond and its carat weight, with modifying effects from the cut,
color, and clarity grades given to the diamond. The relationship is
approximately linear between price and carat when price is transformed to be on
a logarithmic scale and carat transformed to be on a cube-root scale. I found a
somewhat surprising result initially when the marginal trend for the cut, color,
and clarity variables indicated that higher diamond quality was associated with
lower price. However, higher diamond quality was also associated with smaller
diamonds. When I isolated diamonds of a single carat weight, there was a clear
positive relationship between higher diamond quality and higher diamond price.

Outside of the main variables of interest, I verified the relationship between
diamond carat weight and its x, y, and z dimensions. For the dataset given,
there was an interesting interaction in the categorical diamond quality
features. The lower clarity grades looked like they had slightly better
distribution of cut and color grades than diamonds with the higher clarity
grades.


## Key Insights for Presentation

For the presentation, I focus on the these variables: `member_gender`, `user_type`, 
`member_birth_year`, `bike_share_for_all`, `ride_distance` and `duration_sec`. 
I start by introducing the `ride_distance` and `duration_sec` variables.

Afterward, I introduce the relationship between `duration_sec` and `member_birth_year` using a sample of the dataset.

I then introduce the categorical variables by looking at the influence of `member_gender`, `user_type`, 
`member_birth_year`, and `bike_share_for_all` program on both the `ride_distance` and `duration_sec`.


The dataset can be downloaded [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)
