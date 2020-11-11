## Restaurant Revenue Prediction

Tab Food Investments(TFI) is the company behind some of the world's most well-known brands; Burger King, Sbarro, Popeyes, Usta Donerci, and Arby’s. They employ over 20,000 people in Europe and Asia and make significant daily investments in developing new restaurant sites.New restaurant sites take large investments of time and capital to get up and running. When the wrong location for a restaurant brand is chosen, the site closes within 18 months and operating losses are incurred.
We are expected to find a mathematical model to increase the effectiveness of investments in new restaurant sites that would allow TFI to invest more in other important business areas, like sustainability, innovation, and training for new employees. Using demographic, real estate, and commercial data, we would try to predict the annual restaurant sales of 100,000 regional locations.

## Data Description

TFI has provided a dataset with 137 restaurants in the training set, and a test set of 100000 restaurants. The data columns includes the open date, city, city group,type and three categories of obfuscated data: Demographic data, Real estate data, and Commercial data. The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis.

## Data fieds

Id : Restaurant id.

Open Date : opening date for a restaurant

City : City that the restaurant is in. Note that there are unicode in the names.

City Group: Type of the city. Big cities, or Other.

Type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile

P1, P2 - P37: There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include population in any given area, age and gender distribution, development scales. Real estate data mainly relate to the m2 of the location, front facade of the location, car park availability. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators.

Revenue: The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values.

Here is a link to the dataset
https://www.kaggle.com/c/restaurant-revenue-prediction
