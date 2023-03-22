# Cloud-based Big Data Systems Project

## Week1
In week1, I use SageMaker to label training data for Machine Learning.
Reference: https://aws.amazon.com/getting-started/hands-on/machine-learning-tutorial-label-training-data/?nc1=h_ls

1. Use AWS SageMaker to create Jupyter Notebook instance and use python script to download sample dataset.
![image](https://user-images.githubusercontent.com/44468782/223837044-c5aaffc6-d8b4-4465-94ab-af1a89804339.png)
2. In Amazon S3, check if the images dataset is downloaded successfully.
![image](https://user-images.githubusercontent.com/44468782/223837362-f86e855d-b686-49f5-a8b3-f7b13af232eb.png)
3. In SageMaker, create labeling job, wait until the job is completed.
![image](https://user-images.githubusercontent.com/44468782/223837728-ae6a1d2f-4afe-47df-986a-8c17aac2088f.png)
4. Open the output.minifest to see the labeling job result
![image](https://user-images.githubusercontent.com/44468782/223840193-26aea719-b357-4715-a850-63d5db4b7808.png)


## Week2
In week2, I use SageMaker to build and train a Machine Learning Model locally.
I used Amazon SageMaker Studio to locally build a binary classification model using the XGBoost open source library and saved the model artifacts and outputs to Amazon S3. 
![image-20230322151248283](https://user-images.githubusercontent.com/44468782/227016570-5fb22f14-80ea-4a6b-a53d-e5d88adc8342.png)

![image-20230322151229257](https://user-images.githubusercontent.com/44468782/227016631-37ff3f2d-32d0-4b21-8770-a213afb0c453.png)

