INSURANCE RISK APP

This is a simple implementation of what the britecore system does
(Project URL )[http://britcore-peter.s3-website.us-east-2.amazonaws.com/]


## Backend Stack
The backend is build entirely using Django and Django Rest Framework
which makes if fully RESTFul
## Deployment 
The api service is provision using Zappa and AWS lambda 


# Client Stack
The entire client app is build using Vue.JS
Amazon S3 help in serving the statis content which, talks to our api

-- Database is running on MySQL


## Runnning client code in developement
- `cd  client`
- `npm run dev`

## Running server 
- `cd webapp`
- `./manage.py runserver`

## Run test
- `cd webapp`
- `./manage.py runtest`

#### How to use the Application
# Creating a Risk
- User can create a risk type
 ![img](https://github.com/freewayz/britcore-insurance/blob/master/create.png)
# Building Risk Form
User can Build form for a risk type
![imag](https://github.com/freewayz/britcore-insurance/blob/master/builder.png)
# Displaying Risk Form
The form can be displayed
![imag](https://github.com/freewayz/britcore-insurance/blob/master/form-display.png)
