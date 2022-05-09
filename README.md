# Camunda 8: an Introduction Workshop

This repo contains exercises for a n Introduction Workshop about [Camunda 8](https://camunda.com) SaaS. 

:trophy: The Goal of the workshop is to automate a simple process (containing [User Tasks](https://docs.camunda.io/docs/components/modeler/bpmn/user-tasks/), and Service Tasks implemented as [Connectors](https://docs.camunda.io/docs/components/modeler/web-modeler/connectors/) and [Job Workers](https://docs.camunda.io/docs/components/concepts/job-workers/))

**Structure:**  
The Workshop is designed as an Onside Class. You can follow the exercises in the Readme. 
The solution folder contains the solution for each exercise and a more detailed description on how to solve the exercises. 

## Exercise 1: Sign up and create a cluster

This workshop uses Camunda Platform 8 SaaS and so the good news is that you don't have to install anything locally, but you do need to sign up for an account which is free and can be done by following [this link](https://accounts.cloud.camunda.io/signup). 

Once you're signed up you can login to your account at [camunda.io](https://weblogin.cloud.camunda.io). 

Once you're logged into your dashboard simply [follow these instructions](https://docs.camunda.io/docs/components/console/manage-clusters/create-cluster/) in our documenting. 


You'll know you've succeed when your cluster is setup and all the traffic lights are green. 

![Cluster Worker](img/clustersetup.png)

## Exercise 2: Build a process (Web Modeler)
:trophy: Goal of this exercises is to model a BPMN diagram in the Camunda [Webmodeler](https://docs.camunda.io/docs/components/modeler/web-modeler/new-web-modeler/)

**Process Description**
Imagine a known Food Delivery Service with the roles customer, restaurant and driver. Model the process of ordering food from the perspective of the delivery service. Start simple: Limit your model to 3 user tasks. 

You can find a sample solution [here](https://github.com/Nlea/Camunda-8_an_Introduction_Workshop/blob/main/Solution/Exercise02/delivery-process.bpmn)

:tada: You have modeled a BPMN diagramm in the Camunda Webmodeler

## Exercise 3: Make the process executable

## Exercise 4: Service Tasks (Connectors and job workers)

## Exercise 5: Dynamic event handeling
