# Outlier detection with weather data of Tokyo region
## From datasets of 30 years of daily weather
http://www.data.jma.go.jp/obd/stats/etrn/index.php

## Objective

Objective of this notebook is to detect outliers in daily weather over 30 years of weather data of Tokyo region. The dataset is acquired from [Japan Meteorogical Agency](http://www.data.jma.go.jp/obd/stats/etrn/index.php).
I used unsupervised learning from scikit-learn, the methodologies include one class svm, kernel density estimator, local outlier factor, gaussian mixture, isolation forest and elliptic envelope.

### Thanks to the following decks:
https://www.slideshare.net/KosukeNakago/dllab-20180214-88470902 <br>
http://scikit-learn.org/dev/auto_examples/plot_anomaly_comparison.html <br>
http://scikit-learn.org/stable/auto_examples/covariance/plot_outlier_detection.html#sphx-glr-auto-examples-covariance-plot-outlier-detection-py
