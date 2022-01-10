# Sound-Source-Localisation-System

Environment-Specific Microphone Array-Based 3D Sound Source Localization System

Submitted in fulfillment of the requirements for the ENGINEERING DEGREE IN ELECTRICAL AND ELECTRONICS ENGINEERING 


In this work, a microphone array is used in combination with a machine learning approach to estimate the position of a sound source in three different
environments, and testing under various conditions. The sound source localization in this project is performed using features extracted from sound
signals such as the time difference of arrival and the energy difference of sound signals acquired with the microphone array. The microphone array in this
work consists of four microphones placed near the corners of a rectangular room and the estimated position is expressed in terms of coordinates in a
three-dimensional Cartesian system. Extracted features are exploited by a deep artificial neural network trained with the backpropagation algorithm to
output the sound source coordinates. The established localization system is evaluated in three different environments simulated to provide different acoustic conditions.
Results shows that the localization is performed efficiently with an error of 0.019 m at it's best. They also show that using both energy and time of arrival differences leads to better results than using only one of them as input to the neural network.

The Dataset was built from scratch using matlab and the AI model is developed using python
