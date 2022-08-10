# Bike-Sharing-Demand-Prediction-
Capstone Project- Regression, Predicted the Seoul bike demand prediction using supervised regression models.

# Problem Description
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
# Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
## Attribute Information:
Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

''Bike sharing clicks into a higher gear''
Bike rental businesses give customers—who are often, but not necessarily, tourists—bicycles for a short period. Bikes are generally rented for a few hours to recreationally explore the locality. But the customer base might also consist of college students on campus or others who rent for practical reasons.
City bike rentals are particularly popular among tourists who like to explore their destination by bicycle. Usually, the customers of these businesses are most interested in an efficient, comfortable, and safe way of commuting from one place to another. Depending on the destination, weather conditions or the business can be seasonal. However, due to very seasonal industry it can be negatively affected by environmental forecasts and various other variables.
Bike sharing is increasingly attracting more riders in cities around the world for its benefits regarding the urban environment and public health.One critical issue that Seoul is currently facing is the serious air pollution levels. The city’s PM10 and PM2.5 levels maintained considerably high levels in the past few years.
# ''*Go Green*''

# Dataset

![Screenshot 2022-08-09 231021](https://user-images.githubusercontent.com/99437560/183722661-459df77d-c121-4099-a4bd-3fb052579d45.png)
# EDA 
An EDA is a detailed analysis designed to reveal a data set's underlying structure. It is significant for a business because it identifies trends, patterns, and linkages that are not intuitively clear.
# Dependent variable distribution
![download](https://user-images.githubusercontent.com/99437560/183723054-f2ed338f-4643-467b-865c-022da606773a.png)
# Univariate Analysis
Provides summary statistics for each field in the raw data set or summary only on one variable.

The ultimate purpose of a Univariate analysis is to simply explain the data and look for patterns therein.
![download (2)](https://user-images.githubusercontent.com/99437560/183723440-d174d928-0528-4140-a345-f9de7e4ddcbb.png)

# Bivariate Analysis

![download (5)](https://user-images.githubusercontent.com/99437560/183724143-0d49d69c-6b0e-4e6e-bd64-063acbfa89c1.png)
# Multicollinearity
A correlation could be positive, meaning both variables move in the same direction, or negative, meaning that when one variable’s value increases, the other variables’ values decrease. Correlation can also be neutral or zero, meaning that the variables are unrelated.

![download (4)](https://user-images.githubusercontent.com/99437560/183724004-71deb0e5-3317-4586-b14c-c822f8a47fed.png)
# Model Building
A machine learning model is a program that can find patterns or make decisions from a previously unseen dataset.The process of running a machine learning algorithm on a dataset (called training data) and optimizing the algorithm to find certain patterns or outputs is called model training. The resulting function with rules and data structures is called the trained machine learning model.

# Feature Importance

![download (6)](https://user-images.githubusercontent.com/99437560/183725153-48b5c9ea-00e3-4c24-88e8-0f729cf91f6d.png)

# Model performance comparison

![download (7)](https://user-images.githubusercontent.com/99437560/183724904-67a952e7-d123-4453-8e51-201505dd4b56.png)

# Conclusion
The XG Boost model, which predicted the data more accurately, came out on top, followed by Cat Boost and Random Forest for the hypertuned models.

