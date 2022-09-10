# Infrastructure description

![Architecture](../img/Architecture-Diagram.jpg)

## RDS Postgres

Using AWS RDS Postgres as application server database for storing and retrieving information.

Database endpoint: `udagram.cqxbnnpwllwp.us-east-1.rds.amazonaws.com`
![RDS](../img/01-aws-amazon-rds.png)

## Elastic Beanstalk

Elastic Beanstalk extracts and runs the application on an endpoint this application has built and uploaded on s3 bucket.
EB URL: `udagram-api-dev.eba-p2fuwrag.us-east-1.elasticbeanstalk.com` 
![RDS](../img/02-aws-amazon-elasticbeanstalk.png)


## S3 Bucket

The frontend application is deployed using AWS S3 Bucket
Bucket URL: `http://asmaa-udagram.s3-website-us-east-1.amazonaws.com`
![S3](../img/03-aws-amazon-s3-buckets.png)