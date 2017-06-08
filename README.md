# My StartUp.ML Challenge
## Airline On-Time Arrivals - Binary classification model
## Pierre Megret

### The Goal
To use the US Dept. of Transportation on-time arrival data for non-stop domestic flights by major air carriers to predict arrival
delays with a binary classification model.

### The data set
US Dept. of Transportation on-time arrival data for non-stop domestic flights by major air carriers.
The data set corresponds of the month of January 2016, so that I could test my model on all the year.
To predict whether a flight will be delayed or not, here's the features I chose from the USDoT: Day of Week, Unique Carrier,
Flight Number, Origin and Destination airport Id and cities Id, CRS departure and arrival times, ARR_DEL15 dummy, DIVERTED dummy,
Air time, and Distance.

### The Code
The code is organized as follow: an exploration of the data, a k-fold cross-validation error to determine the best hyper-parameters
of my model, and the predictions. All in Jupyter Python Notebook.

#### Part 1. Exploration of the data

Looked at the features of the data as well as the existence of missing values, did some data cleaning.

#### Part 2. Building of the Model

Built a Random Forest Classifier after having tuned it with a grid search cross-validation.

#### Part 3. Predictions and model performances

Evaluated the model performances on different months, on different years.
