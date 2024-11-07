Hello everyone I've uploaded my major project, "Prediction of Parkinson's Disease".This project mainly aims to predict the trained model whether the patient is affected with (PD) Parkinson's Disease or not.


By using ML Algorithm "Random Forest Alogrithm". It is a popular machine learning algorithm that belongs to the supervised learning technique. It can be used for both Classification and Regression problems in ML. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.            
                                                            As the name suggests, "Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset." Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output.

The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.

We have obtained various accuracy results on Trained dataset and Test dataset are:

Train Accuracy: 1.00
Test Accuracy: 0.97.

Requirements are:
pandas,
numpy ,
scikit-learn,
flask,
matplotlib,
click==8.0.1,
Flask==2.0.1,
Flask-MySQLdb==0.2.0,
itsdangerous==2.0.1,
Jinja2==3.0.1,
MarkupSafe==2.0.1,
mysqlclient==2.0.3 &
Werkzeug==2.0.1
