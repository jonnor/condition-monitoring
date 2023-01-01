
# Anomaly Detection


## Resources

* [Awesome Time Seeries Anomaly Detection](https://github.com/rob-med/awesome-TS-anomaly-detection).
Lists software packages and a few labling tools and benchmark datasets.
* [Introduction to Anomaly Detection: Concepts and Techniques](https://iwringer.wordpress.com/2015/11/17/anomaly-detection-concepts-and-techniques/). Very good overview, with recommendations for different cases
* [Twitter: Introducing practical and robust anomaly detection in a time series](https://blog.twitter.com/engineering/en_us/a/2015/introducing-practical-and-robust-anomaly-detection-in-a-time-series.html).
* [](https://anomaly.io/anomaly-detection-using-twitter-breakout/).
Based on Mean Shift Clustering.
Based on algorithm called E-Divisive.
E-Divisive with Medians (EDM) faster version, estimates median using interval trees. 
Mentions Moving Median as a statistic which is robust to anomalies.
* [Anomaly detection and condition monitoring](https://towardsdatascience.com/how-to-use-machine-learning-for-anomaly-detection-and-condition-monitoring-6742f82900d7).
PCA for dimensionalty reduction, and using Mahalanobis distance (MD) threshold for anomaly detection.
AutoEncoder as alternative. Learned dimensionality reduction, using probability distribution of recontruction error for anomaly detect.
Demonstrated on NASA Gear Bearing failure example.
By Axibit AS.
* [Anomaly detection strategies for IoT sensors](https://medium.com/analytics-vidhya/anomaly-detection-strategies-for-iot-sensors-6281e84263df)
Point-wise anomalies: individual devices.
Collective anomalies: multiple devices together.
Contextual anomalies: takes into account context, such as day-of-week etc.

## Methods

* [DeepADoTS](https://github.com/KDD-OpenSource/DeepADoTS).
From paper "A Systematic Evaluation of Deep Anomaly Detection Methods for Time Series". 
Implements 7 deep neural models for anomaly detection.
* [telemanom](https://github.com/khundman/telemanom).
STMs to detect anomalies in multivariate time series data.
Includes anomaly dataset from NASA Mars Rover.

