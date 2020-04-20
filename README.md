# Dataproc_image_processing


Cloud Dataproc is a Google Cloud Platform service for running Spark and Hadoop jobs. It is used for machine learning and big data processing. Cloud Dataproc automation helps you create clusters and manage them easily
This project is in line with the Qwiklabs- ‘Distributed Image processing with cloud Dataproc’. The project consists of processing three images in GCP using Cloud Dataproc to create clusters, buckets and submit Spark jobs. 

Steps-
1.	Log into the GCP account.
2.	Create a development machine.
a.	 Choose VM to create a Virtual Machine. 
b.	Specify the name and type of machine which is to be created- click create.
c.	Once the machine is created SSH into it.
The following steps take place in the SSH terminal
3.	Install scala software and sbt tool (used to build the JAR which contains the program and packages required to run the job).
4.	Set up the Feature Detector File - code taken from githib cloud dataproc repo and them cd into the folder
5.	Launch Build
6.	Create a bucket- done with the help of gsutil program
7.	Download the images into the bucket
8.	Create a Dataproc Cluster
9.	Submit the job to Dataproc- once this is done the images will be stored in the ‘imgs’ folder in the bucket.
The following takes place in GCP console.
10.	Dataproc under the navigation bar in GCP console will show the submitted jobs
11.	Storage will show the images and folders.
12.	Click on one of the images and it can be downloaded in the desktop
13.	We can see the features of the image by dragging the downloaded file in Google Vision AI API.


![Vision AI image](https://user-images.githubusercontent.com/60295261/79699771-9023f100-825f-11ea-825e-f1b51ede02d7.JPG)
