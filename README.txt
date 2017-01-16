==================================================================
Activities of Daily Living (ADLs) Recognition Using Binary Sensors
Version 1.0
==================================================================
Base de datos creada por: Francisco Javier Ordóñez
==================================================================

This dataset comprises information regarding the ADLs performed by two users on a daily basis in their 
own homes. This dataset is composed by two instances of data, each one corresponding to a different 
user and summing up to 35 days of fully labelled data. Each instance of the dataset is described by 
three text files, namely: description, sensors events (features), activities of the daily living (labels). 
Sensor events were recorded using a wireless sensor network and data were labelled manually.

The dataset includes the following files:
=========================================

- 'README.txt'

- 'UserA_Description.txt' - Setting configuration for user 'A'.

- 'UserA_Sensors_training.txt' - Sensor events for user 'A'.

- 'UserA_ADLs_training.txt' - Activity labels for user 'A'.

- 'UserB_Description.txt' - Setting configuration for user 'B'.

- 'UserB_Sensors_training.txt' - Sensor events for user 'B'.

- 'UserB_ADLs_training.txt' Activity labels for user 'B'.

- 'Classify.txt' - Database that you need to classify (sensor data)
- 'ADLs_classifying.txt' - Database that you need to classify (ADLs)

Notes: 
======
- Each sensor event and each activity label is a row on the corresponding text file.

- The format of this dataset is based on the data published by Tim van Kasteren et. al. To obtain further details about such dataset, visit https://sites.google.com/site/tim0306/.
  Both datasets share format and type of sensors, but not the collection of ADLs. However, the characteristics of these datasets are similar enough to be easily included in the same 
  experimentation setup.
c3m.es

Tasks:
==========
1. Visualize the training data and present it in a easy to understand way.
2. Using the training sets, classify the events in 'Classify.txt' and 'ADLs_classifying.txt' between user 'A' and 'B'. 
3. Predict the events (ADLs and sensors) that are missing in the datasets 'Classify.txt' and 'ADLs_classifying.txt', for user A.
4. Explain your choices in algorithms, what are you taking into account, problems you faced and what do you thing would be required for a better solution.








License:
========
Use of this dataset in publications must be acknowledged by referencing the following publication:

	Ordóñez, F.J.; de Toledo, P.; Sanchis, A. Activity Recognition Using Hybrid Generative/Discriminative Models on Home Environments Using Binary Sensors. Sensors 2013, 13, 5460-5477.

This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.
Francisco Javier Ordóñez. November 2013.
