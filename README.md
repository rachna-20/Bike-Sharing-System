# Bike-Sharing-System
Create and train a model for Bike-Sharing-rental system using Linear_Regression
## Attributes
* instant: record index
* dteday : date
* season : season (1:springer, 2:summer, 3:fall, 4:winter)
* yr : year (0: 2011, 1:2012)
* mnth : month ( 1 to 12)
* hr : hour (0 to 23)
* holiday : weather day is holiday or not (extracted from [Web Link])
* weekday : day of the week
* workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
* weathersit :
   * 1: Clear, Few clouds, Partly cloudy, Partly cloudy
   * 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
   * 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
   * 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
* temp : Normalized temperature in Celsius.
* atemp: Normalized feeling temperature in Celsius.
* hum: Normalized humidity. The values are divided to 100 (max)
* windspeed: Normalized wind speed. The values are divided to 67 (max)
* casual: count of casual users
* registered: count of registered users
* cnt: count of total rental bikes including both casual and registered

### About The Bike Sharing System Project
Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.


## methods:
 * import libraries
 * load the data
 * analyse and visualising data
 * EDA(Exploratory Data Analysis)
 * Data Preprocessing
 * Feature Engineering
 * Train the model using Linear Regression

## Libraries used:
* Numpy 
* pandas
* Seaborn
* matplotlib
* scikit learn


## Algorithms used
#### Linear Regression: 
Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting. Different regression models differ based on – the kind of relationship between dependent and independent variables, they are considering and the number of independent variables being used.
