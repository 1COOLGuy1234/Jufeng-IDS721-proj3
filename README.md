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


