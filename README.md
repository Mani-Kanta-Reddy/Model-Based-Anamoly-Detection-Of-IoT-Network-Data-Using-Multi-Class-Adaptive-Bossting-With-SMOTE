# Model-Based-Anamoly-Detection-Of-IoT-Network-Data-Using-Multi-Class-Adaptive-Bossting-With-SMOTE
With the wide range use of Internet of Things in almost all aspects security threads are also growing immensely. Heavy imbalanced nature of IoT security data makes difficult to design a model based anomaly detection in IoT network. It is very challenging for machine learning models to predict the type of anomalies better with great metrics, since most of the machine learning models assumes equal number of samples for each class for better prediction. It is evident or understood from a survey that only 2.79% of the IoT network profiles are of anomaly types which clearly depicts that there are only 3 out of 100 samples are of anomalies. Hence this heavy imbalance nature of IoT data results in poor prediction of an anomaly type in IoT network.
Hence in this work a mutli-class adaptive boosting ensemble based learning technique with Synthetic Minority Oversampling technique (SMOTE) is proposed for prediction of anomaly type in IoT network data. This proposed method uses DS2OS IoT network data taken from Kaggle to train the model. Finally the proposed method’s performance is compared with other machine learning algorithms. The performance metrics like roc-auc-score, sensitivity, f1-score indicates that the proposed model handles the heavy imbalanced nature of IoT network data well and identified as good model for classification of both normal and anomaly types.
This project is implemented with the following 6 machine learning models:
1.	Random Forests
2.	Logistic Regression
3.	Decision Trees
4.	Linear Discriminant Analysis
5.	Multi Layer Perceptron
6.	Adaboost
