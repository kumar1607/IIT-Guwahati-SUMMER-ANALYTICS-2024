# IIT-Guwahati-SUMMER-ANALYTICS-2024

# Problem description
Your goal is to predict how likely individuals are to receive their xyz and seasonal flu
vaccines. Specifically, you'll be predicting two probabilities: one for xyz_vaccine and
one for seasonal_vaccine.

# Performance metric
Performance will be evaluated according to the area under the receiver operating
characteristic curve (ROC AUC) for each of the two target variables. The mean of
these two scores will be the overall score. A higher value indicates stronger
performance.

# I got AUC-ROC score of 0.9999996894895279


#Network Activity Anomaly Detection, by Consulting and Analytics Club, IIT Guwahati
This was the Final Hackathon

#Problem Statement

The dataset contains detailed records of network activities, capturing various attributes associated with network connections. Each record is labeled to indicate whether the activity is normal or a "Neptune" attack, providing a foundation for binomial classification.

A Neptune attack, also known as a SYN flood attack, is a type of denial-of-service (DoS) attack where an attacker overwhelms a target system with a high number of SYN requests, causing the system to become unresponsive to legitimate traffic. It exploits the TCP handshake process to consume resources on the target machine.

The training set contains 86,845 rows, including whether the activity (column - Attack) is normal or not. Use this to train a Machine Learning model, then predict whether the 21,712 entries in the test set have a normal activity or not (Neptune).

Note: 

- In the target variable (Attack), “normal” means normal activity (no attack) i.e., attack = 0

- “neptune” means Neptune attack. i.e., attack = 1
