# AirBNB-EDA

#### Problem
The primary objective of this project is to explore and analyze a dataset of Airbnb listings to uncover valuable insights that can drive business decisions, enhance security, understand customer and host behavior, guide marketing initiatives, and foster innovation.

#### Data
The analysis will be based on the following data sources:</br>
Calendar Data: Contains information about the availability and pricing of listings.</br>
Listings Data: Contains detailed information about each listing, including location, room type, price, and host information.</br>
Reviews Data: Contains reviews and ratings provided by guests for each listing.</br>

#### Pseudocode
1. Download csv from the websites
   - calendar
   - listings
   - reviews

2. Read the CSV file into a DataFrame

3. Initial Data Exploration
   - Display the first few rows of the dataset
   - Check the shape of the dataset (number of rows and columns)
   - Get dataset information (data types, non-null counts)
   - Check for duplicate values
   - Check for missing values and visualize them using a heatmap

4. Understand Your Variables
   - Display column names
   - Generate descriptive statistics for all columns
   - Check unique values for each variable

5. Data Wrangling
   - Create a copy of the dataset
   - Handle missing values by dropping rows with missing data
   - Drop irrelevant columns ('id', 'name', 'host_name')
   - Encode categorical variables using one-hot encoding
   - Check for and drop duplicate values
   - Perform correlation analysis on numerical columns
   - Extract date features from 'last_review' column
   - Bin 'price' into categories and create a new column 'price_range'
   - Calculate review score by multiplying 'number_of_reviews' and 'reviews_per_month'
   - Categorize hosts based on activity levels and create a new column 'host_activity'
   - Calculate listing age based on 'last_review' date
   - Calculate nightly revenue by multiplying 'price' and 'minimum_nights'
   - Categorize availability into bins and create a new column 'availability_category'
   - Calculate distance from city center using latitude and longitude
   - Calculate average length of stay
   - Estimate potential revenue
   - Calculate host tenure based on 'last_review' date
   - Calculate price per bedroom
   - Estimate occupancy rate

6. Data Visualization and Analysis
   - Plot histogram of listing prices
   - Plot bar chart of room types
   - Plot box plot of prices by room type
   - Plot scatter plot of latitude and longitude
   - Plot bar chart of neighborhood groups
   - Plot violin plot of prices by neighborhood group
   - Plot line plot of availability vs price
   - Plot histogram of review scores
   - Plot heatmap of correlation matrix
   - Plot pair plot of key features

7. Insights and Business Impact
   - Analyze and interpret each chart to derive insights
   - Discuss the potential positive and negative business impacts of the insights
