# ECSE 551 MP2
Group 10: Junhao Wang, Yinan Zhou, Ruilin Ji

`Bernoulli_NB_from_scratch.ipynb` contains our code for implementing the Bernoulli Naive Bayes classifier from scratch. It also includes the basic feature construction steps using sklearn and nltk and some preliminary experiments on the Naive Bayes classifier. 

`First_experiments.ipynb` makes use of the off-the-shelf models from the sklearn library. It contains feature construction and experiments with Linear SVM, Logistic Regression, k-nearest Neighbor, Decision Tree, and Multinomial Naive Bayes. A model-only grid search is also implemented in this notebook. 

`feature_selection.ipynb` uses bi-gram and uni-gram to construct features, and performs feature selection. Experiments are conducted using combinations of different sklearn models and different feature sets. 

`grid_search.ipynb` performs grid search on complete sklearn pipelines, including parameters of the features and the models. 

`Keras_NN_model.ipynb` implements the Feedforward Neural Network model that achieved the best test accuracy. It includes feature construction, feature selection, and the model. 

`runtime_accu_exps_visualization.ipynb` performs the experiments with different feature selection schemes and different models. It explores the relationships between feature numbers and runtime and accuracy. It generates the figures used in the report. 
