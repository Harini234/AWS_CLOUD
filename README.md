Building And Deploying Machine Learning Model In AWS Cloud

Tools Used:
1) AWS Sagemaker AI
2) AWS Lambda
3) S3
4) IAM
5) API Gateway
6) Postman - (optional)

Steps for Doing this Project 

-> Create an account in this website "https://aws.amazon.com/"

-> Create a Jupyter notebook by going into AWS Sagemaker AI

-> Write a python code which involves :-
    
    => Data Preparation
    
    => Moving the data to S3 bucket using Boto3 package
    
    => Create XGB model using Sagemaker AI
    
    => Train Model
    
    => Deploy the model

-> Deployment status can be found in AWS Sagemaker AI -> Inference -> Endpoints

-> Create an API in AWS for making prediction using the Endpoints

-> Create inference function using AWS Lambda.

-> In AWS Lambda write the code in the code editor.

-> Go to IAM for creating the new execution role for deploying and testing the code written on AWS Lambda after creating the Inference function.

-> Build the Rest API using API gateway.

-> Cross verify it using Postman API using Post methood.

Conclusion

-> We are using Iris flower dataset for predicting the type of flower in the numeric format.
