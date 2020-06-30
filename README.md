
[image1]: ./WebAppDiagram.svg "Deployment Pipeline"

# Sentiment Analysis Deployment using AWS Services

Build a LSTM model to perform sentiment analysis for movie reviews using IMDB movie reviews dataset. Then, deployed the model and created a public endpoint using the following AWS services : 

- [AWS SageMaker](https://console.aws.amazon.com/sagemaker/home)

  To Build, train, and deploy machine learning models at scale.
- [AWS Lambda](https://console.aws.amazon.com/lambda/home)

  An event-driven, serverless computing platform used a FAAS(Function as a service) that runs code in response to events and automatically manages the computing resources required by that code.
- [API Gateway](https://console.aws.amazon.com/apigateway/main/apis) 

  Used for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale. API developers can create APIs that access AWS or other web services, as well as data stored in the AWS Cloud.
- [Amazon S3](https://s3.console.aws.amazon.com/s3/home)

  Simple Storage Service(S3) provides object storage through a web service interface. Amazon S3 uses the same scalable storage infrastructure that Amazon.com uses to run its global e-commerce network
- [CloudWatch](https://console.aws.amazon.com/cloudwatch/home)

  A monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers to view logs.

The general pipeline of deployment is :

![Deployment Pipeline][image1]

Project Source : [Deep Learning Nanodegree from Udacity](https://www.udacity.com/course/deep-learning-nanodegree--nd101)
