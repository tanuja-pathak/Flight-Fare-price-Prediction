# Flight-Fare-price-Prediction
# Goal of the Project:
The aim of this project is to predict the flight ticket prices based on travel fare data.
# Data Collection:
Data is collected from Kaggle which contains the features Airline,date of journey,source,destination,total stops,etc.
# Exploratory Data Analysis:
* The date of journey is separated into journey date and journey month.
* The departure time and arrival time is separated into hours and minutes.
* Handling the categorical feature Airline,souce and destination by using one hot encoding
* handling the stops categorical feature by label encoding.

The same process is repeated for test dataset.

# Feature Selection:
* Reduce the dimensionality of feature space.
* Selecting a relevant feature from the datatset and removing the redundant and noisy data.

# Train the model:
The model is trained using Random Forest algorithm which predicts the model with the accuracy of 79%.

# Tools used:
JupyterNotebook

# Libraries used:
Numpy, Pandas, Matplotlib, seaborn, scikit-learn, gradio

# Results:
![flightfare resultpng](https://github.com/tanuja-pathak/Flight-Fare-price-Prediction/assets/103842216/a37dd30c-dd3f-4310-bc14-2202b078626f)

![flightfare result2](https://github.com/tanuja-pathak/Flight-Fare-price-Prediction/assets/103842216/468741a7-c3e7-4424-a49b-27fa817872e8)
