# Twitter-Sentiment-Analysis


<p align=center >
<img width="578" alt="Picture1" src="https://user-images.githubusercontent.com/107482510/173815873-46237424-fe24-40da-a055-fe3688786dfe.png">
</p>

This project is to do Sentiment Analysis of tweets from Twitter using AWS services.
The flow of the project is described below:

>We will simulate the Tweets streaming by implementing a Python code that pushes Tweets from our Tweets.json dataset to Kinesis Firehose.

>KDF will receive the Tweets then triggering a Lambda function with the Tweets data.

>Lambda function will send Tweets data to the AWS Comprehend to do Sentiment Analysis.

>Lambda function will receive the result of the Sentiment Analysis from the Comprehend and get it back to KDF to be stored in Amazon S3 bucket.

>We will define a Crawler to create a Data Catalog of the Sentiment Data.

>Athena is now ready to host the new dataset and do queries to explore the data.

>Now, we can create account on Quicksight and integrate it with Athena dataset to do some data visualization.


AWS Services used in the project:
  1. Amazon Kinesis Data Firehose 
  2. AWS Lambda
  3. Amazon Comprehend
  4. Amazon Simple Storage Service (S3)
  5. AWS Glue
  6. Amazon Athena
  7. Amazon QuickSight
