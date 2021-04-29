# [Project 1: DataMidWare - A Data Middleware Python Library: Project Overview](https://github.com/JagritiG/data-middleware)

**DataMidWare** is a data middleware python library which ***accelerates data preparation, analysis, and visualization*** tasks by integrating
different technologies, software, and libraries using its APIs.

The **DataMidWare** performs the following tasks:
- Provides direct interactions with database, data preparation & processing tool, algorithm library, and data visualization tool using its APIs.
- Imports and parses raw data (csv, json, txt, xml) from different sources and load to database (MySQL, NoSQL).
- Produces clean data from raw format and stores into database for analysis
- Performs SQL queries using its APIs
- Performs data analysis on the data stored in database
- Provides direct visualization of csv, json data, and data stored in database
- Exports data in different format (csv, json) from database.

# [Project 2: gsheets-db-api-plus: A Python DB API 2.0 for Google Spreadsheets (0.2.0): Overview](https://github.com/JagritiG/gsheet-db-api-plus)
This version (0.2.0) allows you to query, insert, update, and delete Google Spreadsheets using SQL and SQLAlchemy.
The version (0.2.0) removes the limitations in [version (<= 0.1.12)](https://github.com/betodealmeida/gsheets-db-api) for insert, update, and delete operations.
#### Examples using SQLAlchemy grammar
##### INSERT:
```
engine.execute(table.insert(), column1=value1, column2=value2, column3=value3, ...)
```
##### UPDATE:
```
engine.execute(table.update().where(table.c.column == value).values(column1=value1, column2=value2, column3=value3,...))
```
##### DELETE:
```
engine.execute(table.delete().where(table.c.column <= value))
```

# [Project 3: WebViz: Web Visualization using Django and Plotly: Project Overview](https://github.com/JagritiG/django-webviz)
This is a simple Django app for web visualization which allows users to upload csv file and visualize the data.

# [Project 4: Geo-location Clustering using the k-means Algorithm using Python: Project Overview](https://github.com/JagritiG/Coursera_Capstone/blob/main/notebook/capstone_project_the_battle_of_neighborhoods_report_week2.ipynb)
The objective is to discover a few most promising neighborhoods based on the criteria such as knowing neighborhood, place with no similar restaurants in vicinity, accessibility and visibility of the location, population base, parking, and low crime rate, and present them with statistics so that the stakeholders, the restaurant entrepreneurs, can select the precise location for opening up their new restaurant.
#### Methodology used:
- Python geopy library to obtain the geographical coordinates of San Diego.
- The Foursquare API to segment and explore the neighborhoods as well as the latitude and longitude coordinates of each neighborhood. For this, I have set the limit as 100 and the radius 1000 meter for each neighborhood from their given latitude and longitude information.
- The Folium library to visualize the neighborhoods in San Diego with neighborhoods superimposed on top.
- The explore function to get the most common venue categories in each neighborhood and then used this feature to group the neighborhoods into clusters with the help of K-means clustering algorithm.
- The Folium library to visualize the neighborhoods in San Diego and their emerging clusters.
- The demographical as well as property facts data about San Diego neigborhoods to rate them based on these data, and merge them with related clusters of neighborhoods.
- The Folium library to visualize final selected locations for opening up a restaurant based on the criteria mentioned

# [Project 5: California Housing Price Prediction using Multivariate Regression Model: Project Overview](https://github.com/JagritiG/machine_learning/blob/main/projects/house_price_prediction_regr_v1.ipynb)
- Predict future house price using existing California housing data.
- Perform supervised learning to develop a powerful ML model.
- We use Regeression model to predict the future house price.
- As house price depends on many parameters, we build multivariate regression model.
- Use Train/Test Split to split the data for training and testing.
- Train our model with train data set.
- Evaluate the model against our test dataset.
