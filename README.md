# ML Workflow

The aim of the project is to try to define a functional continuous delivery workflow for machine learning projects.

The pipeline is divided in 3 sub-modules:

* `data_layer` -> fetch the data from an open data hub and prepare for the next layer.
* `model_layer` -> here the data is taken and used to train a machine learning model, the artifact produced here is used by the next layer.
* `serving_app` -> here the magic provided by machine learning is used in a simple web application.