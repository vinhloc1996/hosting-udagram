## Udagram Infrastructure

![Architecture](udacity-hosting-udagram-Architecture.jpg)

### AWS
#### RDS Postgres
The application server need to store data into database. AWS RDS is used to do this

Database URI: `postgresql://postgres:password@udagram.c5okwf63s1k9.us-east-1.rds.amazonaws.com/udagram`

#### Elastic Beanstalk
The application server is deployed on AWS Elastic Beanstalk service

EB URL: `http://udagram-api-dev2222.us-east-1.elasticbeanstalk.com/`

#### S3 Bucket
The UI is deployed on AWS S3 Bucket

Bucket URL: `http://udagram-frontend-nd0067.s3-website-us-east-1.amazonaws.com/`

Please access from the bucket url to use the application
