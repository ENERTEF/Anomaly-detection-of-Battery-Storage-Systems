# Anomaly detection

The anomaly detection service is presented in a jupyter notebook with a ready to run example. 

One of the biggest challenges associated to such classification exercise is the absence of abnormal data and labeled data in general. Another one is the often subjective threshold applied to the classification boundary. 

We follow an unsupervised ML approach to classify time series observations. The service describes the methodology including a combination of a Gaussian Mixture Model (GMM) and a One Class Support Vector Machine (OCSVM) algorithms, introducing an adaptive threshold. The algorithm can assess off-line datasets or incoming messages, explaining a mechanisms to trigger an alarm for an intervention based on frequency of events. 

Potential applications are various in the RES node such as Wave Energy Converters (WEV), Wind generation assets or Storage assets.
