# The 45th President of United States Twitter Report

![Build Status](https://codebuild.us-east-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoieWJldWpxN0xKbUlwNWJMdlh3UC80bE1GTTVtaTYzL1pndlNXVFBlSllZaU5Ed3l3aEM4L01SVzV4UnVXNlhxaURSSkFRNVVkWDRnU1lSNk5KQytMcnpFPSIsIml2UGFyYW1ldGVyU3BlYyI6IlpCSVlkWTh1enRsRFpEd2IiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

This is my Flask web application hosted on AWS Elastic Beanstalk: http://flask-web-evn.eba-2xusf33v.us-east-1.elasticbeanstalk.com/. I'm interested in how does President Trump feel after he lose the election so I built a website to update his top 20 most recent tweets and perform sentiment analysis on them every 7 hour. 


## Motivation

I'm trying to exercise good practive during development cycle and learn about cloud computing through the process. The project accomplishs CI/CD with AWS CodeBuild and CodePipeline and is deployed with AWS Elastic Beanstalck.

## Features

- 100% on Cloud
- Severless Web Application 
- Easy to customize and scale
- Continuous Integration + Continuous Deployment

## Screenshots

Website screenshot:
![web page](./resources/2.png)

CodePipeline screenshot:
![CD](./resources/1.png)


## Framework

Project Diagram: 
![diagram](./resources/3.png "Diagram")
Top part of the diagram(anything above Cloudwatch service) is for my serverless-data-pipeline project: https://github.com/wensu425/aws-data-pipeline.git

