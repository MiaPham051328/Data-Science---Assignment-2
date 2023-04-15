# Pipelnes using Pycaret3, Scikit-learn and Yellowbrick

# Overview
In this assignment, I still use the Capstone project's processed dataset ([Hotel Revenue](https://www.kaggle.com/datasets/govindkrishnadas/hotel-revenue)) and build pipelines related to the is_canceled field.

# Details
* Part 1: Demonstrating a pipeline by using Pycaret3
I will load the dataset and set up feature engineering using PyCaret's setup() function then I train several machine learning models using PyCaret's compare_models() function. This function trains and evaluates several models on the data and returns a summary of the results, which I can use to select the best-performing model. After the model training is complete, I will create, tune, evaluate and finalize which model is recommended as best.

* Part 2: Demonstrating a pipeline by using Scikit-learn and Yellowbrick
Based on the model training results of part 1 I will choose another model to demonstrate the pipeline. If in part 1 I chose classification model, in part 2 I will choose regression model.After loading the data I will use get_dummies and train_test_split which are two common functions in machine learning used for data preprocessing and model training respectively. Then I will import the necessary libraries related to the pipeline and the regresion model, I will use the Scikit-Learn estimator to estimate them so that they have fit(), predict() and score() methods, and passed in as the last step in the Pipeline. Finally, I create a yellowbrick heatmap visualization (confusion matrix) that shows each combination of the correct and predicted classes for a test dataset.

# Technologies Used
* Pandas
* Pycaret3
* Scikit-learn
* Yellowbrick

# Visualization

![Alt text](images/heatmap.png)

# Work-through

Click [Data visualization](https://clipchamp.com/watch/ryLiwxBbQ0Y) to watch the video.

![Alt text](images/boxplot.png)
