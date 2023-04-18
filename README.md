# Pipelnes using PyCaret3, scikit-learn and Yellowbrick

# Overview
In this assignment, I still use the Capstone project's processed dataset [Hotel Revenue](https://www.kaggle.com/datasets/govindkrishnadas/hotel-revenue) and build pipelines related to the is_canceled field.

# Details
* Part 1: Demonstrating a pipeline by using Pycaret3

I will load the dataset and set up feature engineering using PyCaret's setup() function then I train several machine learning models using PyCaret's compare_models() function. This function trains and evaluates several models on the data and returns a summary of the results, which I can use to select the best-performing model. After the model training is complete, I will create, tune, evaluate and finalize which model is recommended as best.

* Part 2: Demonstrating a pipeline by using scikit-learn and Yellowbrick

Based on the model training results of part 1 I will choose another model to demonstrate the pipeline. If in part 1 I chose classification model, in part 2 I will choose regression model. After loading the data I will use get_dummies and train_test_split which are two common functions in machine learning used for data preprocessing and model training respectively. Then I will import the necessary libraries related to the pipeline and the regresion model, I will use the scikit-learn estimator to estimate them so that they have fit(), predict() and score() methods, and passed in as the last step in the Pipeline. Finally, I create a yellowbrick heatmap visualization (confusion matrix) that shows each combination of the correct and predicted classes for a test dataset.

# Technologies Used
* [pandas](https://pypi.org/project/pandas/)
* [PyCaret3](https://pycaret.org)
* [scikit-learn](https://scikit-learn.org/stable/index.html)
* [Yellowbrick](https://www.scikit-yb.org/en/latest/index.html)

# Visualization
Part 1: Pycaret Pipeline

![Pycaret Pipeline](https://user-images.githubusercontent.com/122539964/232178699-720c3df3-3144-41cb-9a9e-fa9fb1bed344.png)

Part 2: Yellowbrick Confusion Matrix

![Confusion Matrix](https://user-images.githubusercontent.com/122539964/232178755-3b08c869-7dc2-4e17-b8b1-0bcd0c3d6bbc.png)

# Work_through

Click [Pipelines] to watch the video.

### Some of evaluation models of part 1

* Feature Important Plot

![Feature Important](https://user-images.githubusercontent.com/122539964/232178832-0d6f1316-2aa9-420b-8d0d-0d966312d371.png)

* Random Forest Classifier Classification Report

![RF Classification Report](https://user-images.githubusercontent.com/122539964/232178842-a7910acb-c233-4698-a4fb-eb833bccfdbf.png)
