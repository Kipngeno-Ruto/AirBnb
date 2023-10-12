**# Airbnb-Price-Model**
people often  travel worldwide for business, work touring places, etc., and because of this, many will want to know the accommodation prices in these places, this project thus aims to solve this challenge, by exploring different prices of Airbnb in the US


**Data Collection**
The data used here is from a public repository containing the data of  NY for 2019


**Data Wrangling/Preparation**
After collecting the data, we explore it to find patterns and solve data quality problems since raw data usually come in a 'noisy' format
some columns for instance last_review_date in object format which needed conversion to datetime format, among the many inconsistencies that the data had


**Exploratory Data Analysis**
Here is another crucial stage  of the life cycle where get insights about the data, questions like the prices between various cities, which cities most  tourists/travelers love the most are answered, the room types most people love, and so forth

**Data Preprocessing**
Our ML algorithm works best with numbers hence the need to convert all non-numerical columns to numerical
Data standardization is also another important process here, in most cases, the data coming from experiments or any data collection
the process is not normally distributed and therefore there is a need to standardize the data for the algorithm to perform better

**Modeling**
Finally, we chose two algorithms, linear regression, and RandomForest and from the training, Random Forests performance turned out to be 
better than the Linear Model

