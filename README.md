<h1>Optimizing Solar Panel Plant Management: Energy Forecasting,
Performance Classification, and Anomaly Detection</h1>

This project focused on optimizing the management of two solar panel plants through pre-
dictive analytics, performance classification, and anomaly detection. We began by performing an extensive
exploratory data analysis (EDA), which helped us clean the dataset and identify key features. We applied
various statistical models to predict energy production, classify panel performance, and detect anomalies.
For energy production forecasting we analyzed the performance of:

• Multiple Linear Regression
• Multiple Linear Regression with Forward Stepwise Feature Selection
• Lasso Regression
• Decision Tree Regressor
• Random Forest Regressor

and found that the Random Forest Regressor was the most effective model,
achieving an impressive R2 score of 99.7% for the first plant and 94.7% for the second. This high level of
accuracy highlights the model’s ability to handle non-linear relationships and complex datasets, making it
an ideal choice for energy prediction tasks.


In classifying panel performance we compared the following models:

• Multinomial Logistic Regression
• Linear Discriminant Analysis (LDA)
• K-Nearest Neighbors (KNN)
• Random Forest Classifier


and found that the Random Forest Classifier outperformed other models, achieving an
overall accuracy of 80%. This model demonstrated its superiority over multinomial logistic regression, LDA,
and KNN by efficiently capturing non-linear interactions and resisting overfitting, particularly when dealing
with diverse data types.

Finally, we developed an anomaly detection tool using the predictions from the Random Forest Regressor.
This tool allows plant operators to identify potential failures in real time, helping to prevent costly repairs
and unplanned downtime. By flagging anomalies early, the tool ensures that underperforming inverters or
panels can be addressed before they cause significant damage or loss of productivity.
Overall, this project demonstrates the value of advanced machine learning techniques in enhancing the oper
ational efficiency of solar panel plants. By improving energy prediction, identifying underperforming units,
and preventing failures through anomaly detection, this analysis contributes to the broader goal of making
renewable energy systems more reliable, efficient, and cost-effective. Future improvements could focus on
incorporating time-series forecasting models or neural networks to further enhance prediction accuracy and
extend the capabilities of the anomaly detection tool.


