# Airport Classification at Scale with Apache Spark ML
![alt text](results.png)

## Description
Predict whether a flight will arrive late based on the following features: Day of the month, day of the week, carrier, origin airport ID, destination airport ID, departure delay.
 
Built with Spark ML and PySpark, prediction is achieved on a large dataset efficiently.

## Results                     
+---------+------------------+
|   metric|             value|
+---------+------------------+
|       TP|           74338.0|
|       FP|             561.0|
|       TN|          648994.0|
|       FN|           86978.0|
|Precision| 0.992509913349978|
|   Recall|0.4608222370998537|
|       F1|0.6294096479901784|
+---------+------------------+

Area under ROC = 0.9238796257535625
