In order to clarify the results, we detail below the libraries and parameters used.

## Libraries
- **Scikit-learn** (version 0.21.3): is a free software machine learning library for the Python programming language
- **NLTK** (version 3.4): is a leading platform for building Python programs to work with human language data. 
- **Pandas** (version 0.22.0): is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language. 
- **SciPy** (version 1.4.1): is a free and open-source Python library used for scientific computing and technical computing. 

## Multilayer Perceptron

Params:

- activation='relu'
- alpha=0.0001
- batch_size='auto'
- beta_1=0.9
-  beta_2=0.999
- early_stopping=False
- epsilon=1e-08
- hidden_layer_sizes=(100,)
- learning_rate='constant'
- learning_rate_init=0.001
- max_iter=200
- momentum=0.9
- n_iter_no_change=10
- nesterovs_momentum=True
- power_t=0.5
- random_state=None
- shuffle=True
- solver='adam'
- tol=0.0001
- validation_fraction=0.1
- verbose=False
- warm_start=False

## Decision Tree

Params:
- class_weight=None
- criterion='gini'
- max_depth=None
- max_features=None
- max_leaf_nodes=None
- min_impurity_decrease=0.0
- min_impurity_split=None
- min_samples_leaf=1
- min_samples_split=2
- min_weight_fraction_leaf=0.0
- presort=False
- random_state=None
- splitter='best'

## Random Forest
Params:
- bootstrap=True
- class_weight=None
- criterion='gini'
- max_depth=None
- max_features='auto'
- max_leaf_nodes=None
- min_impurity_decrease=0.0
- min_impurity_split=None
- min_samples_leaf=1
- min_samples_split=2
- min_weight_fraction_leaf=0.0
- n_estimators='warn'
- n_jobs=None
- oob_score=False
- random_state=None
- verbose=0
- warm_start=False

## KNeighbors
Params:
- algorithm='auto'
-leaf_size=30
- metric='minkowski'
- metric_params=None
- n_jobs=None
- n_neighbors=5
- p=2
- weights='uniform'
