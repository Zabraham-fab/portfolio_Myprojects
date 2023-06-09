# Portfolio_projects

# AWS

## 1-Project-001 : Roman Numerals Converter Application (Python Flask) deployed on AWS EC2 with Cloudformation and AWS CLI

The Roman Numerals Converter Application aims to convert the given number to the Roman numerals. The application is to be coded in Python and deployed as a web application with Flask on AWS Elastic Compute Cloud (EC2) Instance using AWS Cloudformation and CLI Services.

## 2-Project-004 : Phonebook Application (Python Flask) deployed on AWS Application Load Balancer with Auto Scaling and Relational Database Service using AWS Cloudformation

The Phonebook Application aims to create a phonebook application in Python and deployed as a web application with Flask on AWS Application Load Balancer with Auto Scaling Group of Elastic Compute Cloud (EC2) Instances and Relational Database Service (RDS) using AWS Cloudformation Service.

## 3-Project-006 : Kittens Carousel Static Website deployed on AWS Cloudfront, S3 and Route 53 using Cloudformation

Kittens Carousel is a static website application deployed on AWS Simple Storage Service (S3), served through Cloudfront and Route 53 using AWS Cloudformation Service.

## 4-Project-101 : Kittens Carousel Static Website deployed on AWS EC2 using Cloudformation

Kittens Carousel is a static website application deployed with Apache Web Server on AWS Elastic Compute Cloud (EC2) Instance using AWS Cloudformation Service.

________________________________________________________________________________________________________________________________________________________________

# DevOps

## 1-Project-202 : Phonebook Application (Python Flask) deployed on AWS Application Load Balancer with Auto Scaling and Relational Database Service using Terraform

<img src="img/tf-phonebook.png">

The Phonebook Application aims to create a phonebook application in Python and deployed as a web application with Flask on AWS Application Load Balancer with Auto Scaling Group of Elastic Compute Cloud (EC2) Instances and Relational Database Service (RDS) using Terraform.

## 2-Project-203: Dockerization of Bookstore Web API (Python Flask) with MySQL

<img src="img/203-bookstore-api.png">

Bookstore Web API Application aims to create a bookstore web service using Docker to give students the understanding to dockerization of an application. The application code is to be deployed as a RESTful web service with Flask using Dockerfile and Docker Compose on AWS Elastic Compute Cloud (EC2) Instance using Terraform.

# Project-206: Microservice Architecture for Phonebook Web Application (Python Flask) with MySQL using Kubernetes

<img src="img/Microservice_structure.png">

Phonebook Microservice Web Application aims to create a web application with MySQL Database using Docker and Kubernetes to give students the understanding of Microservice architecture. In this application, we have a frontend service and a backend service to interact with database service. Each service will be managed by a Kubernetes deployment. The backend service will be a gateway for the application and it will serve the necessary web pages for create, delete and update operations while the frontend service will serve a search page in order to conduct read operations. To preserve the data in the database, persistent volume and persistent volume claim concepts should be adopted.

## 3-Project-207 : Web Page Application (Postgresql-Nodejs-React) deployed on EC2's with Ansible and Docker

<img src="img/ansible.png">

<img src="img/todo_web.png">

The Clarusway Web-Page Application aims to deploy web-page written Nodejs and React Frameworks on AWS Cloud Infrastructure using Ansible. Building infrastructure process is managing with control node utilizing Ansible. This infrastructure has 1 control node and 3 EC2's as worker node. These EC2's will be launched on AWS console. Web-page has 3 main components which are postgresql, nodejs, and react. Each component is serving in Docker container on EC2s dedicated for them. Postgresql is serving as Database of web-page. Nodejs controls backend part of web-side and react controls frontend side of web-page. The code was written by Clarusway's Developers and architecture will be created by Clarusway's AWS & DevOps Team.

## 4-Project-208: Jenkins Pipeline for Web Page Application (Postgresql-Nodejs-React) deployed on EC2's with Ansible and Docker

<img src="img/ansible-208.png">

<img src="img/todo_web-208.png">

This project aims to create a Jenkins pipeline to deploy web-page written Nodejs and React Frameworks on AWS Cloud Infrastructure using Ansible. Building infrastructure process is managing with control node utilizing Ansible. This infrastructure has 1 jenkins server (`Amazon Linux 2 AMI`) as ansible control node and 3 EC2's as worker node (`Red Hat Enterprise Linux 8 with High Availability`). These EC2's will be launched on AWS console. Web-page has 3 main components which are postgresql, nodejs, and react. Each component is serving in Docker container on EC2s dedicated for them. Postgresql is serving as Database of web-page. Nodejs controls backend part of web-side and react controls frontend side of web-page. The code was written by Clarusway's Developers and architecture will be created by Clarusway's AWS & DevOps Team.