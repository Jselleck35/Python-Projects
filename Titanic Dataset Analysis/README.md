Titanic Dataset Analysis

On April 15, 1912, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew.
This tragedy shocked the world and led to better safety regulations for ships. Here, we perform exploratory data analysis,
in particular by applying machine learning to predict which passengers survived the tragedy.

Steps:
- Data acquisistion of the Titanic Dataset
  - Train dataset
  - Test dataset
 
- Perform Exploratory Data Analysis for the train dataset
  - Passengers age distribution
  - Passengers survival buy age
  - Passengers survival breakdown
  - Passengers class distribution
  - Passengers embarkation by locations
  
- Perform machine learning to train the machine model and
  - Create user defined function to load train data set
  - Create user defined function to load test datas set
  - Create machine model
  - Train the machine
  - Predict whether a passenger survidied the tragedy or not
  - Persist the model for future re-use
  
Here is a detailed description of the given datasets: 
- PassengerId : ID of passenger
- Survived    : 0 = No, 1 = Yes
- Pclass      : Ticket Class 1 = 1st, 2 = 2nd, 3 = 3rd
- Name        : Name of Passenger
- Sex         : Sex of Passenger
- Age         : Age in years
- SibSp       : # of siblings / spouces aboard the Titanic
- Parch       : # of parents / children aboard the Titanic
- Ticket      : Ticket number
- Fare        : Passenger fare
- Cabin       : Cabin number
- Embarked    : Point of Embarkation C = Cherbourg, Q = Queenstown, S = Southampton
  
  
  The data for this project can be found at https://www.kaggle.com/c/titanic/data
