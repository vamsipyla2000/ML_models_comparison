# ML_models_comparison
Car Evaluation data set was taken, the ML problem is to  predict the acceptability of the car using the features, such as price, maintenance , doors, number of persons it can accommodate, luggage boot area,safety
Two mdoels accuraacy of ML models such as random forest,ANN  was compared.
Accuracy of random forest classifier with 10 estimators and all the features is 0.9475
Accuracy of random forest classifier with 100 estimators and all the features is 0.9545
Accuracy of random forest classifier with 10 estimators and all removing two least features is 0.8546
Accuracy of random forest classifier with 10 estimators and all removing two least features is 0.9264
It was concluded that all the features have significant importance in model building.
Accuracy of different optimizers was plotted with respect to the learning rate, it is observed that for RMSprop optimizer gave more accuracy(Maximum accuracy: 0.9369527101516724) compared to ADAM and AdaGrad
learning rate of 0.01 gave more accuracy with RMSprop optimizer.
Random forest gave better accuracy than ANN model, and ANN model is computationally expensive.
Random Forest: Random Forest is an ensemble method that combines multiple decision trees to reduce overfitting and increase generalization. It is relatively robust and performs well even without extensive hyperparameter tuning. The simplicity and interpretability of decision trees help Random Forests capture the structure in the data effectively without overfitting.
ANN (Artificial Neural Networks): ANNs are highly flexible and capable of modeling complex relationships in data. However, they require careful tuning of various hyperparameters (e.g., number of layers, number of neurons per layer, learning rate) and are prone to overfitting, especially with small datasets or insufficient regularization. This can result in lower accuracy if the model does not generalize well.
