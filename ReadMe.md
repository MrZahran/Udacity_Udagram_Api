# Udagram - Full-Stack Application

### Architecture Diagram For How The Project Works

![Architecture Diagram](https://raw.githubusercontent.com/MrZahran/Udacity_Udagram_Api/main/udagram/screenshots/diagram.jpg)

<br />

## Infrastructure

Udagram application composed from backend && frontend

##### Front-end

- Is Angular App on S3 Bucket AWS

##### Back-end

- Is Express App on Elastic Beanstalk Env. on AWS

<br />

## App Dependencies

##### Node

##### express

##### AWS CLI

##### RDS

##### S3

##### Angular

##### bcrypt

##### body-parser

##### dotenv

##### jsonwebtoken

##### pg

##### sequelize

<br />

## Pipeline Description

#### CircleCI Pipeline Events Include:

1. Spin up environment
2. Preparing environment variables
3. Install Node.js
4. Install Front-End Dependencies
5. Install API Dependencies
6. Front-End Build
7. API Build
8. Front-End Deployed To AWS S3
9. Back-End Deployed To Elastic Beanstalk
