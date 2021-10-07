# fault-detection-using-machine-learning

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info

There is a need to identify abnormalities in data so as to predict faults in equipments way before they break down.
This project uses concepts statistics such as mean and variance to build a sliding window that learns from the data and makes 
a prediction of possible faults.

	
## Technologies
Project is created with:
* Python

## Dataset
There are 6 recordings of magnetic flux measured on a supra conducting magnet.

* Signal1 to Signal6 contains magnetic flux readings. It is a regularly sampled signal (Te=5ms)

* Jump1 to Jump6 is a boolean signal of the same length as Signal. When a row in Jump1 to Jump6 is equal to 1, a flux jump is present. 
Jump1 to Jump6 thus localizes periods of time when a flux jump occurred.

* Dataset is saved in CSV file format.


	
## Setup
