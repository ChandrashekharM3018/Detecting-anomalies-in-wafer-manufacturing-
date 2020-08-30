# Detecting-anomalies-in-wafer-manufacturing-

Detecting Anomalies can be a difficult task and especially in the case of labeled datasets due to some level of human bias introduced while labeling the final product as anomalous or good. 
These giant manufacturing systems need to be monitored every 10 milliseconds to capture their behavior which brings in lots of information and what we call the Industrial IoT (IIOT). 
Also, hardly a manufacturer wants to create an anomalous product. Hence, the anomalies are like a needle in a haystack which renders the dataset that is significantly Imbalanced. 

Capturing such a dataset using a machine learning model and making the model generalize can be fun. In this , we have such a use-case from one of India's leading manufacturers of wafers(semiconductors).
The dataset collected was anonymized to hide the feature names, also there are 1558 features that would require some serious domain knowledge to understand them.

Dataset Description:

1.Train.csv - 1763 rows x 1559 columns
2.Test.csv - 756 rows x 1558 columns
3.Sample Submission.csv - Please check the Evaluation section for more details on how to generate a valid submission
 

Attribute Description:

1.Feature_1 - Feature_1558 - Represents the various attributes that were collected from the manufacturing machine
2.Class - (0 or 1) - Represents Good/Anomalous class labels for the products
