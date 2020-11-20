Managing the Complete Machine Learning Lifecycle with MLflow
=============================================================
![](./images/mlflow-workshop.png)

Module 4 of 4
-------------
Other parts:
- [Module 2](../projects/README.md)
- [Module 3](../models/README.md)
- [Module 4](../model_registery/README.md)

Content for the MLflow Workshop Series
---------------------------------------
Machine Learning (ML) development brings many new complexities beyond the traditional software development lifecycle. Unlike in traditional software development, ML developers want to try multiple algorithms, tools and parameters to get the best results, and they need to track this information to reproduce work. In addition, developers need to use many distinct systems to productionize models.

To solve these challenges, [MLflow](https://mlflow.org), an open source project, simplifies the entire ML lifecycle. MLflow introduces simple abstractions to package reproducible projects, track results, 
encapsulate models that can be used with many existing tools, and central respositry to share models,
accelerating the ML lifecycle for organizations of any size.

Goal and Objective
------------------
Aimed at beginner or intermediate level, this four-part modules aims to educate data scientists or ML developer in how you 
leverage MLflow as a platform to track experiments, package projects to reproduce runs, use model flavors to deploy in diverse environments, and manage models in a central respository for sharing.

What you will learn
-------------------
Understand the four main components of open source MLflow——MLflow Tracking, MLflow Projects, MLflow Models, and Model Registry—and how each compopnent helps address challenges of the ML lifecycle.
 * How to use [MLflow Tracking](https://mlflow.org/docs/latest/tracking.html) to record and query experiments: code, data, config, and results.
 * How to use [MLflow Projects](https://mlflow.org/docs/latest/projects.html) packaging format to reproduce runs
 * How to use [MLflow Models](https://mlflow.org/docs/latest/models.html) general format to send models to diverse deployment tools.
 * How to use [Model Registry](https://mlflow.org/docs/latest/model-registry.html) for collaborative model lifecycle management
 * How to use [MLflow UI](https://mlflow.org/docs/latest/tracking.html#tracking-ui) to visually compare and contrast experimental runs with different tuning parameters and evaluate metrics


Instructor
-----------

- [Jules S. Damji](https://www.linkedin.com/in/dmatrix/) [@2twitme](https://twitter.com/2twitme) 
---


About the MLflow Model Registry module 4
----------------------------------------
In this module 4, we will cover:

 * Concepts and motivation behind and Model Registry
 * Tour of the the Model Registry API Documentation
 * Understand Model Registry Workflow
    * UI Workflow
    * API Workflow
 * How to create models and register them
 * How to use Pyfunc Model Flavor to load models from Model Registry
 * Use the Model Registry UI on Jupyter Lab (local host) or Google Colab

Prerequisites
-------------
* Python 3, pip, and conda pre installed
* Knowledge on how to use conda
* Knowledge of Python 3 and programming in general
* Preferably a UNIX-based, fully-charged laptop with 8-16 GB, with a Chrome or Firefox browser
* Familiarity with GitHub, git, and an account on Github
* Some knowledge of Machine Learning concepts, libraries, and frameworks
 * scikit-Learn
 * pandas and Numpy
* Loads of virtual laughter, curiosity, and a sense of humor ... :-)

How to get the Workshop Material
---------------------------------

1. Familiarity with git is important so that you can get all the material easily during 
the tutorial and workshop as well as continue to work on in your free time, after the 
session is over.

```git clone git@github.com:dmatrix/olt-mlflow.git or git clone https://github.com/dmatrix/olt-mlflow.git```

Setup your conda environment for Jupyter Lab and MLflow
-------------------------------------------------------

1. `cd tmls-workshop`
2. `conda create --name jupyter-mlflow`
3. `conda activate jupyter-mlflow`
4. `pip install -r jupyter_requirements.txt`
5. `python -m ipykernel install --user --name=mlflow`
6. Run `mlflow --help` to check that MLflow's was correctly installed
7. cd `cd model_registery/notebooks/` 
8. `jupyter lab &`
9. Open the `run_weather_forecast.ipynb` notebook

Just flow with MLflow!
