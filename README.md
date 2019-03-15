# pedestrian_crossing_predictions
This repository contains two approaches to building a classifier that will predict whether a pedestrian will cross in front of a vehicle. There is a Random Forest (RF) implementation and a Recurrent Neural Network (RNN) implementation.

The problem was initially presented to me as a coding interview assignment from Perceptive Automata, but I decided to put more effort into it and try different methods.
The dataset used was curated by Perceptive Automata through the opensource JAAD dataset (http://data.nvision2.eecs.yorku.ca/JAAD_dataset/).

This data is dashcam footage where each frame has been tagged with information. First I go through and perform some data wrangling and feature engineering to turn the data into an acceptable format for the RF or RNN. In the feature engineering stage I create additional features based upon whether certain actions have occured already.

This was originally written in Spring 2018, and I'm currently revisitng the project (March 2019). 
