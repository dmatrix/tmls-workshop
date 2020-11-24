Managing the Complete Machine Learning Lifecycle with MLflow
=============================================================
![](./images/mlflow-workshop.png)

Module 3 of 4
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
Concepts and motivation behind and Models
Tour of the the MLflow Model API Documentation
How to create different model flavors
Pyfunc Model Flavor: what and how to use it


About the MLflow Models module 3
--------------------------------

In this module 3, we will cover:
 * Concepts and motivation behind and Models 
 * Tour of the the MLflow Model API Documentation
 * How to create different model flavors
 * Pyfunc Model Flavor: what and how to use it
 * Use the MLflow UI on the DCE

Prerequisites
-------------
* Before the session, please pre-register for [Databricks Community Edition](https://databricks.com/try-databricks)
* Knowledge of Python 3 and programming in general
* Preferably a UNIX-based, fully-charged laptop with 8-16 GB, with a Chrome or Firefox browser
* Familiarity with GitHub, git, and an account on Github
* Some knowledge of Machine Learning concepts, libraries, and frameworks 
     * scikit-learn
     * pandas and Numpy
     * matplotlib
     * Keras/TensorFlow
* [**optional for module-1**] PyCharm/IntelliJ or choice of syntax-based Python editor
* [**optional for module-1**] pip/pip3 or conda and Python 3 installed
* Loads of virtual laughter, curiosity, and a sense of humor ... :-)

Obtaining the Tutorial Material
--------------------------------

Familiarity with **git** is important so that you can get all the material easily during the tutorial and
workshop as well as continue to work in your free time, after the session is over.

``` git clone github.com:dmatrix/tmls-workshop.git or git clone https://github.com/dmatrix/tmls-workshop.git```

Documentation Resources
-----------------------

This tutorial will refer to documentation: 

1. [MLflow](https://mlflow.org/docs/latest/index.html) 
2. [Numpy](https://numpy.org/devdocs/user/quickstart.html)
3. [Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)
4. [Scikit-Learn](https://scikit-learn.org/stable/index.html)
5. [Keras](https://keras.io/optimizers/)
6. [TensorFlow](https://tensorflow.org)
7. [Matplotlib](https://matplotlib.org/3.2.0/tutorials/introductory/pyplot.html)

How to get started
-------------------
We will walk through this during the session, but please sign up for [Databricks Community Edition](https://databricks.com/try-databricks) before the session :

1. ``` git clone git@github.com:dmatrix/olt-mlflow.git ```
2. Use this [URL](https://community.cloud.databricks.com/login.html) to log into the Databricks Community Edition

![](../images/databricks_ce_loging.png)

3. Create a ML Runtime 7.4 with Spark 3.0.1 Cluster

![](../images/databricks_ce_create_mlr.png)

4. In the brower: 
  * (1) Go the GitHub **projects/notebooks/dbc/** subdirectory
  * (2) Download **MLflow-Models.dbc** file on your laptop

5. Import the **MLflow-Projects.dbc** file into the Databricks Community Edition

![](../images/databricks_ce_import_notebooks.png)

Let's go!

Cheers,

Jules


