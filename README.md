# flight_fare_prediction
## Problem Statement
With the increasing preference for air travel over other modes of transportation, predicting flight fares has become crucial for travelers looking to optimize their travel costs. Flight fares fluctuate based on various factors such as timing, destination, duration, and seasons. This project aims to predict flight fares to help travelers plan economically.
### Project Approach
#### 1. Data Exploration
##### Tools Used: Pandas, Numpy
##### Objective: Understand the structure and content of the dataset.
##### Steps:
Loaded the dataset. Checked for missing values and basic statistics.

#### 2. Data Visualization
##### Tools Used: Matplotlib, Seaborn
##### Objective: Gain insights into the relationships between variables.
##### Steps:
Plotted heatmaps to visualize missing values. Created count plots for categorical features like airlines. Used histograms and box plots to understand distributions and detect outliers.

#### 3. Feature Engineering
##### Objective: Enhance the dataset with meaningful features.
##### Steps:
Extracted date and time features from the departure and arrival times. Encoded categorical variables such as airlines, source, and destination. Calculated the duration of flights. Handled missing values by imputing or removing them as necessary.

#### 4. Model Selection
##### Objective: Identify the best machine learning model for prediction.
#### Steps:
Tested various regression models to establish a baseline accuracy. Evaluated models using residual plots. Selected the best model based on accuracy and fit.

#### 5. Hyperparameter Tuning
##### Tools Used: GridSearchCV, RandomizedSearchCV
##### Objective: Improve model performance.
##### Steps:
Tuned hyperparameters of the selected model.

#### 6. Model Deployment
##### Objective: Create a user interface for predicting flight fares.
##### Tools Used: Flask, HTML, CSS
##### Steps:
Developed a web application using Flask. Created forms to input flight details. Displayed predicted fares to the user. Running the Project

##### Prerequisites
Python 3.x Flask Pandas Numpy Scikit-Learn Matplotlib Seaborn

##### Technologies Used
Python Scikit-Learn Flask HTML, CSS Pandas, Numpy

Cross-validated to avoid overfitting.

##### Contributing
If you find any bugs or have suggestions for improvements, please raise an issue or submit a pull request.

##### Contact
shiny Email: shinyshajeev@gmail.com LinkedIn:

Gobikrishnan Email: gobikrishnanm1999@gmail.com LinkedIn:http://www.linkedin.com/in/gobikrishnanm1999

Sriram Email: sriram.natarajan94@gmail.com LinkedIn:http://www.linkedin.com/in/sriram-natarajan94
