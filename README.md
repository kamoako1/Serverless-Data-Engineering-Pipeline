# Individual Project 4: Serverless Data Engineering Pipeline

This project includes reproducing the architecture serverless data engineering cycle with the following functionalities:

 - Creating SQS called producer
 
 - Creating a table called Fang with Dynamo DB
 
 - Creating an AWS Lambda Function
 
 - Creating a trigger with Cloud Watch, so the function will be called every minute with more message production. Helpful for checking automation.
 
 - Creating another lambda environment called consumer for S3.
 
   Consumer will grasp wikipedia entries and write it to S3. It will apply sentiment analysis results into a bucket I created called "Fangsentiment1"
   
 - Checking the status of bucket in S3. The bucket gives the ability to see what is includes as far as sentiment results.
 
 - Choose CSV files to download. Each csv file will graph sentiment from wikipedia, and print sentiment result for a particular company.
