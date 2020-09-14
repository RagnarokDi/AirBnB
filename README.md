# AirBnB
Projects with public AirBnB datasets

## What determines Airbnb listing prices in New York?

In this project, I am trying to identify the most important features determining the listing price for Airbnb properties.

There are currently no free services to help Airbnb hosts decide how to price their listing. Airbnb itself suggests the choice is “completely up to you” (Airbnb, 2020) and recommends searching for similar listings in the neighbourhood. Given the public availability of web-scraped data from Airbnb of many properties and their listings, the following report investigates what features seem to be most useful in predicting price per night. The analysis will look at more than 80 features, and will then use the 36 most relevant ones to compare and contrast 3 different very popular models - **Decision Tree, Boosted Trees (XGBoost) and Random Forests**. There are a range of engineered features such as the number of neighbouring properties in a given 1,250-metre-radius, nearby venues and their rating and the presence of amenities. 

The best model is within a **factor of 1.45** from the actual prices with **70% R2** and shows that price setting is a highly competitive exercise with the price of nearby properties along with the type of property a host is offering are the most important features.
