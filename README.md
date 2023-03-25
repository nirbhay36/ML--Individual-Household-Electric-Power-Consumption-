# ML--Individual-Household-Electric-Power-Consumption-

![image](https://user-images.githubusercontent.com/105970953/215973615-ab53f7fd-619c-48d2-9f79-32429b86e2b1.png)


## Problem Statement :


To predict the individual household electricity consumption depending on the following attributes.



## Attribute Information:


date: Date in format dd/mm/yyyy

time: time in format hh:mm:ss

global_active_power: household global minute-averaged active power (in kilowatt)

global_reactive_power: household global minute-averaged reactive power (in kilowatt)

voltage: minute-averaged voltage (in volt)

global_intensity: household global minute-averaged current intensity (in ampere)

sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered)

sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.

sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.


## I have performed


Data ingestion

Exploratory data analysis

Handling the outliers

Store the preprocessed data in mongoDB

Retrive data from mongoDB

Model Building

Standardize Scaler

Dump the preprocessed data into pickle file

Linear Regression

Ridge Regression

Lasso Regression

ElasticNet Regression

Report ( Summary )
