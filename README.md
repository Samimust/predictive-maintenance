
# Preventive Maintenance
##### First Capstone Project - Springboard DS Career Track

### Problem:

Failure prediction is a major topic in predictive maintenance in many industries. Airlines are particularly interested in predicting equipment failures in advance so that they can enhance operations and reduce flight delays. 

Observing engine's health and condition through sensors and telemetry data is assumed to facilitate this type of maintenance by predicting Time-To-Failure (TTF) or Remaining Useful Life (RUL) of in-service equipment. Using aircraft engine's sensors measurements, can we predict engine's TTF?.

### Client:

In a predictive maintenance scenario provided by Microsoft, A fictitious airline Company is trying to utilize historical data of equipment sensors to make data-driven decisions on its maintenance planning.  Based on this analysis, the company will be able to estimate engine's time-to-failure and optimize its maintenance operations accordingly.


### Data:

Text files contain simulated aircraft engine run-to-failure events, operational settings, and 21 sensors measurements are provided by Microsoft. It is assumed that the engine progressing degradation pattern is reflected in its sensor measurements.  
___Training Data:___  The aircraft engine run-to-failure data.
[download trianing data](http://azuremlsamples.azureml.net/templatedata/PM_train.txt)  
___Test Data:___ The aircraft engine operating data without failure events recorded.
[download test data](http://azuremlsamples.azureml.net/templatedata/PM_test.txt)  
___Ground Truth Data:___ The true remaining cycles for each engine in the testing data.
[download truth data](http://azuremlsamples.azureml.net/templatedata/PM_truth.txt)



### Approach:

By exploring the aircraft engine’s sensor values over time, the machine learning algorithm can learn the relationship between the sensor values and changes in sensor values to the historical failures in order to predict failures in the future.
Regression modeling algorithms could be used to predict the number remaining cycles before engine failure. 
Classification modeling algorithms could be used to predict if the engine will fail within specific cycles window or not (binary classification), or to predict in which cycles window will the engine fail (multi-class classification).


### Deliverables:

- Project code, well-documented on github  
- Final project paper

