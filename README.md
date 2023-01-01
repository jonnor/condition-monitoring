
# Condition Monitoring

Some notes on monitoring the condition of machines and equipments using sensors and Machine Learning.

## Resources

- [datasets](./datasets.md)

## Tasks

- [Changepoint Detection](./tasks/changepoint-detection.md)
- [Anomaly Detection](./tasks/anomaly-detection.md)
- Remaining Useful Life Prediction

## Sensing

- [Vibration](./sensing/vibration.md)


## Answers


## Using standard Anomaly Detection methods for time-series data

Feature engineering to represent time and event statistics.
[1](https://datascience.stackexchange.com/questions/56296/anomaly-detection-in-a-database/82287#82287)

## Setting decision threshold

Without having access to labeled data.
Estimate the Positive rate, and use a budget to review them.
[1](https://datascience.stackexchange.com/questions/104210/how-to-set-threshold-value-by-looking-at-loss-distribution-in-anomaly-detection/104839#104839)

## Anomaly Detection using Sound

DCASE community has researched actively last year.
[1](https://datascience.stackexchange.com/questions/117043/sound-anomaly-detection/117227#117227)

## Explaining Anomaly Detection predictions

Explaining IsolationForest using SHAP values with the snap Python library.
[1](https://stats.stackexchange.com/questions/404017/how-to-get-top-features-that-contribute-to-anomalies-in-isolation-forest/451518#451518)

## Anomaly Detection in spatial data

Using a standard anomaly detector after Binning or Clustering the 2D (X,Y) space.
[1](https://datascience.stackexchange.com/questions/81142/looking-for-spatial-clusters-and-anomalies-is-dbscan-the-right-tool/81266#81266)

## Use of labeled in unsupervised Anomaly Detection

Anomaly Detection is normally learned in an unsupervised / one-class manner.
Often the training set is assumed to consist only of the "normal" class,
which can be done without having labels.
Howver a labeled dataset is still incredibly useful for validation and testing sets,
where it is used for

- Hyper-parameter optimization. Selecting the anomaly threshold, feature/preprocessing settings, etc.
- Estimating performance on unseen data ("generalization")
- Estimating the robustness of our AD model pipeline

[1](https://datascience.stackexchange.com/questions/77832/cross-validation-in-anomaly-detection-with-labelled-data/82291#82291)
 

## False Positive Supression using few-shot classifier

Using a few-shot classifier on labeled data in combination with unsupervised Anomaly Detector.
Useful to avoid too many False Positives.

- [1](https://stackoverflow.com/questions/64533169/suppressing-false-positives-incorrectly-classified-as-outlier-anomaly-in-anoma/64570101#64570101)
- [Anomaly Detection with False Positive Suppression (relayr.io)](https://relayr.io/technology-blog/anomaly-detection-with-false-positive-suppression/).
- [SNIPER: Few-shot Learning for Anomaly Detection to Minimize False-negative Rate with Ensured True-positive Rate](https://ieeexplore.ieee.org/document/8683667)


## Misc

Avoiding missing data at beginning/end of time-series when using (large) sliding time-windows, by doing bidirectional processing.
[1](https://stackoverflow.com/questions/69926526/interval-prediction-for-a-time-series-anomaly-in-time-series/69940939#69940939)
