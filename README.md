
# Preventive Maintenance
#### First Capstone Project - Springboard DS

### Problem:

Failure prediction is a major topic in predictive maintenance in many industries. Airlines are particularly interested in predicting equipment failures in advance so that they can enhance operations and reduce flight delays. 

Observing equipment's health and condition through sensors and telemetry data is assumed to facilitate this type of maintenance by predicting Time-To-Failure (TTF) or Remaining Useful Life (RUL) of in-service equipment. This project will try to validate this assumption.


### Client:

In a predictive maintenance scenario provided by Microsoft, A fictitious Airline Company is trying to utilize historical data of equipment sensors to make data-driven decisions on its maintenance planning.  Based on this analysis, the company will be able to estimate equipment time-to-failure and optimize its maintenance operations accordingly.


### Data:

Text files contain simulated aircraft engine run-to-failure events, operational settings, and 21 sensors measurements are provided by Microsoft. It is assumed that the engine progressing degradation pattern is reflected in its sensor measurements.
Training Data:  The aircraft engine run-to-failure data.
http://azuremlsamples.azureml.net/templatedata/PM_train.txt
Test Data: The aircraft engine operating data without failure events recorded
http://azuremlsamples.azureml.net/templatedata/PM_test.txt
Ground Truth Data: The true remaining cycles for each engine in the testing data
http://azuremlsamples.azureml.net/templatedata/PM_truth.txt



### Approach:

By exploring the aircraft engine’s sensor values over time, the machine learning algorithm can learn the relationship between the sensor values and changes in sensor values to the historical failures in order to predict failures in the future.
Regression modeling algorithms could be used to predict the number remaining cycles before engine failure. 
Classification modeling algorithms could be used to predict if the engine will fail within specific cycles window or not (binary classification), or to predict in which cycles window will the engine fail (multi-class classification).


### Deliverables:

Project code, well-documented on github and Final project paper

