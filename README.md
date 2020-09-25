# Getting Started with Amazon SageMaker Studio

This folder contains a [Jupyter notebook that will demonstrate the main features of Amazon SageMaker Studio](xgboost_customer_churn_studio.ipynb). It is designed to be run from within Studio. It is an example of creating a model to predict customer churn using the XGBoost algorithm.

## Features

* [Amazon SageMaker Experiments](https://docs.aws.amazon.com/sagemaker/latest/dg/experiments.html)
  * Manage multiple trials
  * Hyperparameter experimentation & charting
* [Amazon SageMaker Debugger](https://docs.aws.amazon.com/sagemaker/latest/dg/train-debugger.html)
  * Debug your model 
* [Model hosting](https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works-hosting.html)
  * Set up a persistent endpoint to get predictions from your model
* [SageMaker Model Monitor](https://docs.aws.amazon.com/sagemaker/latest/dg/model-monitor.html)
  * Monitor the quality of your model
  * Set alerts for when there are deviations in the model's quality

## Prerequisites

You must have already [on-boarded with Amazon SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-studio-onboard.html) and be able to login to Studio.  If not, please follow these steps.
1. From the top right Region menu, Select Oregon or us-east-1. 
2. Go to AWS Management Console, Select Amazon SageMaker.
3. Amazon SageMaker Studio should be at the top of your menu selection, click on the link to show the Amazon SageMaker Studio Control Panel.
4. You should see a Get started Section, Select Quick Start, fill in a default user name, Choose then create a new IAM Role.
5. Under the new IAM Role, select "Any S3 bucket", Create the IAM role and return to main menu.
6. Click on Submit to Start the SageMaker Studio provisioning process, this is a once time process and, it may take a few minutes. 

> If you are looking to delete the Studio you've just created later, follow the steps of deleting apps from user menu, and then the user, and finally SageMaker Studio.


## How to run this notebook

1. Login to [Amazon SageMaker Studio] by clicking on the "Open Studio" butotn next to your user name. it should open a seperate Tab, loading a Jupyterlab based IDE.

2. Open a terminal within Studio:  File -> New Terminal.  

![open a terminal](./images/open_a_terminal.gif)

3. Clone this repository with the following command.

```bash
git clone https://github.com/awslabs/amazon-sagemaker-examples.git
```

![clone the repo](./images/clone_the_repo.gif)

4. Use Studio's file manager to find and open the notebook.

Open the notebook: aws_sagemaker_studio/getting_started/xgboost_customer_churn_**studio**.ipynb

5. Select the Python3 Data Science Kernel.
6. Change your Instance type from Unknown to t3.xlarge.

![find the notebook](./images/find_and_open_the_notebook.gif)

