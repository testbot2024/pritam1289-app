# Project pritam1289-app 
    
Description apple mango data done

## 1. Introduction   

This is a **frontend boilerplate template application** built using the Wrappid framework, which enables simultaneous development of web and mobile application.   
This guide will help us setup and run application using Wrappid framework.


## 2. Getting Started

This getting started section will help you setup a basic application built using the Wrappid framework. Follow the below steps to get going.

[2.1. What are my Pre-requisites?](#21-what-are-my-pre-requisites)


First you need to verify that your system fulfills the pre-requisites. Listed below are the things required to be available in your system.

- Node.js - version 16
- npm - version 8
- @wrappid/toolkit installed globally


### 2.1. What are my Pre-requisites?

- [Refer here](https://github.com/wrappid/#1-check-pre-requisites)
- install [@wrappid/toolkit](https://github.com/wrappid/#2-install-wrappid-toolkit) globally


### 2.2. How to Create?

It is expected that you have successfully installed @wrappid/toolkit(wrappid framework's CLI tool) and initialised it.
Run the below command to create Frontend Wrappid Project


Run the below command to setup a wrappid-app in mobile runtime-environment.

bash
cd <wrappid>-<app>
wrappid setup mobile


### 2.4. How to Start?
You can start a frontend app in two modes:
- [Static (Without Backend Service)]()   
- [Dynamic (With Backend Service)]()

- **Static (Without Backend Service)**
Run the below command to start the development frontend server for web:
bash
cd wrappid-app
wrappid start web


This should launch your default browser with a URL http://localhost:3000

Run the below command to start the development server for mobile:

bash
cd wrappid-app
wrappid start mobile


This should launch your emulated device (provided a proper setup is done on the Android Device Manager)


- **Dynamic (With Backend Service)**

To start Dynamic Fontend Wrappid project, you'll first need your Wrappid Backend up and running. [steps for backend]().   
 - Enter you Backend URL in wrappid.conf.json file located at the root of wrappid-app project.   
 - Follow the same steps for starting a [static frontend wrappid-app]()   

## 3. What are Wrappid App Environments
Wrappid App can be runned in 3 environments:
- Dev: Suitable for Development
- Stage: Suitable for Testing
- Prod: Suitable for Production

By default, Wrappid App project setups and starts in dev environment.
These environments are to be configured in wrappid.conf.json located at the root of wrappid-app project

To run a Wrappid App project in a different environment, run the below command:
terminal
cd wrappid-app
wrappid start [web|mobile] --env=[dev|stage|prod]

### 3.1 What are Wrappid App Runtime Environments?

Frontend Wrappid-App has two runtime-environments:
- Web
- Mobile


pritam1289-app is created using the wrappid framework.
    url link or original template: [Original Template Wrappid](https://github.com/wrappid/wrappid-app)

