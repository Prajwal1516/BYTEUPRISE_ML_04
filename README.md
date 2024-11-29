# House Price Predictor 
House Price Prediction Model using Linear Regression.

# House Price Prediction with Linear Regression

This repository contains a Data Science and Machine Learning project that predicts house prices using a linear regression model. The model leverages key features such as median income, housing median age, total rooms, total bedrooms, and population to estimate house values in California.

# **Dataset**
The dataset used in this project is sourced from the California housing dataset, which includes geographical and socioeconomic information about houses in various locations. The dataset is provided in a CSV format (housing.csv).

# **Features**
* longitude: Longitude coordinate of the house location.
* latitude: Latitude coordinate of the house location.
* housing_median_age: Median age of houses in the area.
* total_rooms: Total number of rooms in the house.
* total_bedrooms: Total number of bedrooms in the house.
* population: Total population in the area.
* households: Total number of households in the area.
* median_income: Median income of households in the area.
* ocean_proximity: Proximity of the house to the ocean (categorical variable).**

# **Project Structure**
The project is organized as follows:
* housing.csv: The raw dataset file.
* data.dropna(): Dropping the missing values.
* data.info(): Processed data after handling the missing values.

# **Requirements**
* Python 3.x
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

# **Model Training and Evaluation**
The linear regression model is trained using the median_income, housing_median_age, total_rooms, total_bedrooms, and population features to predict median_house_value. Model evaluation metrics include:
* Test Result = reg.score(x_test_s, y_test)
* Improved Test Result = forest.score(x_test_s, y_test)
