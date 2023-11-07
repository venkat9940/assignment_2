# assignment_2
1) The provided data (link above) contains various details and attributes associated with used cars. The
target variable, which is the central focus of analysis, is the price of the used cars, and it is measured in
lakhs. The data in this dataset is tabular, with rows and columns, where each row represents a specific
used car listing, and each column represents a particular attribute or feature of these cars. Features are
Make and model of the car, Location or city of sale, Year of manufacture, Mileage, Odometer
(kilometers driven), Fuel type (petrol or diesel), Transmission type (manual or automatic), Number of
owners, Engine displacement, Engine horsepower, Number of seats, and Price when the car was new.
Use this data to perform the following:
a) Look for the missing values in all the columns and either impute them (replace with mean,
median, or mode) or drop them. Justify your action for this task. (5 points)
b) Remove the units from some of the attributes and only keep the numerical values (for
example remove kmpl from “Mileage”, CC from “Engine”, bhp from “Power”, and lakh from
“New_price”). (5 points)
C) Change the categorical variables (“Fuel_Type” and “Transmission”) into numerical one hot
encoded value. (5 points).
d) Create one more feature and add this column to the dataset (you can use mutate function in
R for this). For example, you can calculate the current age of the car by subtracting “Year” value
from the current year. (5 points)
