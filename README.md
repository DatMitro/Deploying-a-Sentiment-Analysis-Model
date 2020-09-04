# SageMaker Deployment Project

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).

### Contents

* General Outline
* Step 1: Downloading the data
* Step 2: Preparing and Processing the data
* Step 3: Upload the data to S3
* Step 4: Build and Train the PyTorch Model
* Step 5: Testing the Model
* Step 6: Deploying the model for testing
* Step 7: Use the model for testing
* Step 6 (again): Deploy the model for the web app
* Step 7 (again): Use the model for the web app

### Note

This project was completed as part of my [Machine Learning Nanodegree](https://confirm.udacity.com/GWCSDDH3) and has passed the requirements as fully functional, but if you try to write your review in the web app you won't get any results. That's because the amazon endpoint which applies that algorithm and returns the results doesn't have the option to turn on only for incoming requests and keeping it on forever is too costly.
