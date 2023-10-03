# Final-Project-Tableau

## Project/Goals
The main goal of this project is to introduce us to the actual, real world raw data and how we can convert this data to a meaningful, structured and accurate format.
Make this presentable using visualizations,create attractive and interactive Dashboards to impress stackholders and get the meaningful conclusion from it.This is a subset of the challenges we have to face while analysing and presenting real world problem.

## Process
### Selecting Data: 
I choose the Option 2 -> III) AIRBNB (NYC data)
As I am a have used Airbnb and also I have little experience in handling Listings.
### Exploring: 
I start with deep diving into data to get the better understanding of the dataset. I start exploring the each table and then column of the table and try to be more familiar with it. For ths I use two tools. At first I use capabilities of python to understand the data also side by side I use Tableau to make some graphs(Teal colored worksheets) to figure out the data structure. I also use Excel as my dataset is .xlsx format.
### Cleaning:
Then I start with the cleaning process. Initially I start with the easy going cleaning which are easy to detect and fix. For example eliminating NULL valued rows, removing duplicate rows & columns, deleting null columns. Python is a great tool to do that in no-time. I have also detect some pattern in data using Tableau plots. for example on sheet(Geomap) I found some of the zipcodes are not belongs to New York City. I also refer to the zip code data of US to compare the zipcodes and found that there are some outliers present in the data. I also studied that NYC zip have some pattern(like 10050). I use this pattern and eliminate these using the Tableau calculated field (NYC Zipcode).
### Analysing:
I analyse 
  - Room Type 
  - Beds
  - Price
  - Neighbourhood
  - Host Since
  using plots and showme tables to get the more insite about the BI.(Green Colored Sheets)
### Questions:
I decide to explain following questions (Red colored sheets):
 - Which areas of NYC are having more dense listings and are expensive Geographically.
 - Which Neighbourhood is more expensive for users.
 - What are the top 10 Host IDs by Total Reviews.
 - How popular the Airbnb is among the Hosts in NYC.
 - Which type of listings are there in Airbnb-NYC.
### Interesting Facts about data:
while working with this data I found some interesting outcomes.
- No of beds: no of beds present in different listings are varying . But there are few listings available having incredibally large no of beds like 16(Refer sheet: Study Beds). So It would be quite interesting how big that property is.
- Manhattan Neighbourhood is one of the most popular having most mo of listings and most expensive neighbourhood in NYC.
### Forcasting: 
Using forcasting in Tableau we can predict the amount of listings added by hosts in year-2016. it comes out to be a hike in no of listings registed.
### Clustring:
We apply clustring on Price/Rating data(refer clustering sheet). The following outcomes found from clustering
cluster 1: It shows there are listings present having High Price-> Low Rating.
cluster 2: In this segment both are proportional.
cluster 3: it shows the listings having Low Price ->High Rating
## Results
I succeed to find the answers of the above questions clearly using an interactive dashboard. With this dashboard stackholders could easily detect the impact of various factors that could attract the users as well as hosts.

## Challenges 
- The data does not contains any Sales information.
- It also does not contains Bookings information.
- Due to the lack of the above information the actual profit gained by the stackholders is hard to determine which might be the main Point of Interest for them.

## Future Goals
I would like to connect this Airbnb-NYC dataset with the Sales and Bookings dataset to create the actual Business Developemnt Dashboard.
