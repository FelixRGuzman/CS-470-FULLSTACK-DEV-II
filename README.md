# CS 470 | Full Stack Development II: Cloud Development
 
## Overview

This repository contains the final reflection for CS 470: Full Stack Development II at SNHU. Throughout this course, I migrated a locally-hosted full-stack MEAN application (MongoDB, Express, Angular, Node.js) into a fully serverless AWS architecture, working through containerization, cloud storage, serverless functions, NoSQL database migration, and cloud security.
 
## Presentation

Video Presentation: https://www.youtube.com/watch?v=dNtf_Jtdlm0
 
## What was done

As stated previously, this course followed a step-by-step cloud migration of a full-stack MEAN application. Particularly, it was done so by utilizing containerization technology to create Dockerfiles for the Angular frontend and Node.js API as well as Amazon S3 for detaching and hosting the said angular frontend. In this process we created several AWS Lambdas to replace Node.js backend functions, routed requests through Amazon's API Gateway and also replaced MongoDB with DynamoDB by recreating the necessary data models and partition keys. Everything was secured through AWS IAM functionality which enabled identity and access management roles following the principle of least privilege.
 
## Technologies Used

- Docker / Docker Compose
- Amazon Web Services (S3, Lambda, API Gateway, DynamoDB, IAM)
- Angular (frontend)
- Node.js / LoopBack (original API)
- MongoDB to DynamoDB (database migration)

## Repository Contents

- CS470 Final Reflection Guzman Felix.pdf: My final reflection covering experiences, strengths, and planning for growth.
