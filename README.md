# Classification Project of Bank Data

This dataset is about bank marketing. The binary classification goal is to predict if the client will subscribe to a bank term deposit. It contains information about 41,188 clients as well as social/economic context (20 attributes) between May 2008 and November 2010.

This project attempts to build a classification model to predict whether or not the client will subscribe to a bank term deposit. Three machine learning models, namely Support Vector Machine, Logistic Regression and Random Forest, are compared. All of the three models are cross-validated. 

Results show that the Random Forest model outperforms the other two models, with ROC AUC of 0.94 and recall of 0.93, meaning successfully predicts 93% of the future clients. Also, it is computationally efficient.

The analysis result shows that last contact duration is the most important factor in prediction, and some of the economic indicators (i.e., employment rate, Euribor three month rate) come next.

The details of the data are described in [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, In press, http://dx.doi.org/10.1016/j.dss.2014.03.001
