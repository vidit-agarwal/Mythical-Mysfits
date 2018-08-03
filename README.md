# Mythical Mysfits

In this repo, I've build modern application on AWS. Modern applications isolate business logic, optimize reuse and iteration, and remove overhead everywhere possible. Modern apps are built using services that enable you to focus on writing code while automating infrastructure maintenance tasks.
<br>
Mythical Mysfits enables the visitors to adopt a fantasy creature (mysfit) as pet.

## Sneap Peak

This web application is collection on a front-end web server and connect it to a backend database. I've set up user authentication and will be able to collect and analyze user behavior.
<br>
The site provides basic functionality such as ability to “like” your favorite mysfit and reserve your chosen mysfit for adoption. It also allows you to gather insights about user behavior for future analysis.
<br>

## Modules

The application architecture diagrams provide a structural representation of the services that make up Mythical Mysfits and how these services interact with each other.<br>

> _Following are the modules_

1) `Create Static Website` : Build a static website, using Amazon Simple Storage Service (S3) that serves static content (images, static text, etc.) for your website. 
2) `Build Dynamic Website` : Host your application logic on a web server, using an API backend microservice deployed as a container through AWS Fargate.
3) `Store Mysfit Data` : Externalize all of the mysfit data and persist it with a managed NoSQL database provided by Amazon DynamoDB.
4) `Add User Registration` : Enable users to registration, authentication, and authorization so that Mythical Mysfits visitors can like and adopt myfits, enabled through AWS API. Gateway and its integration with Amazon Cognito.

5) `Capture User Clicks` : Capture user behavior with a clickstream analysis microservice that will record and analyze clicks on the website using AWS Lambda and Amazon Kinesis Firehose. 

