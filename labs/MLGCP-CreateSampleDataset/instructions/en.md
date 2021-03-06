# Create a sample dataset


## Overview

*Duration is 1 min*


This lab is part of a lab series where you train, evaluate, and deploy a machine learning model to predict a baby's weight.

In this lab \#2, you sample the full BigQuery dataset to create a smaller dataset for model development and local training. In the real world, it's much better to start out simple and develop your TensorFlow code locally on a small subset of data, then scale it out to the cloud. Developing on a smaller subset of data speeds up model development and makes debugging easier.

![3862a7e90f775ad6.png](img/3862a7e90f775ad6.png)

### What you learn

In this lab, you will learn how to:

* Sample a BigQuery dataset to create datasets for ML
* Preprocess data using Pandas


## Setup


![[/fragments/start-qwiklab]]


## Create Storage Bucket

*Duration is 2 min*


![[/fragments/create-bucket]]


## Launch Cloud Datalab


![[/fragments/setup-datalab]]


## Clone course repo within your Datalab instance


![[/fragments/clone-repo-in-datalab]]

## Create sampled dataset

*Duration is 15 min*


Sample a BigQuery dataset to create datasets for ML

__Step 1__

In Cloud Datalab, click on the __Home__ icon, and then navigate to __datalab \> notebooks \> training-data-analyst \> courses \> machine\_learning \> deepdive \> 06\_structured \> labs__ and open __2\_sample.ipynb__.

<aside class="warning"><p>Note: If the cloud shell used for running the datalab command is closed or interrupted, the connection to your Cloud Datalab VM will terminate. If that happens, you may be able to reconnect using the command ‘<strong>datalab connect mydatalabvm</strong>&#39; in your new Cloud Shell. Once connected, try the above step again.</p>
</aside>

__Step 2__

In Datalab, click on __Clear | Clear all Cells__. Now read the narrative and execute each cell in turn:

* If you notice sections marked "Lab Task", you will need to create a new code cell and write/complete code to achieve the task.
* Some lab tasks include starter code. In such cells, look for lines marked \#TODO.
* Hints may also be provided for the tasks to guide you along. Highlight the text to read the hints (they are in white text).
* If you need more help, you may take a look at the complete solution by navigating to : __datalab \> notebooks \> training-data-analyst \> courses \> machine\_learning \> deepdive \> 06\_structured__ and open __2\_sample.ipynb__.

<aside class="warning"><p>Note: When doing copy/paste of python code, please be careful about indentation</p>
</aside>

![[/fragments/endqwiklab]]

Last Tested Date: 12-10-2018

Last Updated Date: 12-18-2018

![[/fragments/copyright]]
