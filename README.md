# Serverless Framework Node HTTP API on AWS

This template demonstrates how to make a simple HTTP API with Node.js running on AWS Lambda and API Gateway using the Serverless Framework. 

I created a simple ToDo using the **Database of AWS DynamoDB** and used **MiddleWare middy** to Body Parser JSON http. 

It consists of __4 Lambda functions__:

- add a Todo
- fetch all the Todos-
-  fetch an individual Todo by the id
- Updates a Todo _to completed: true (for example)_


## Creation of TodoTable

![ScreenShot of TodoTable](https://i.ibb.co/FBGnPdz/Captura-de-pantalla-2022-02-03-a-las-11-35-23.png)

## Creation of Lambda AWS Node
![ScreenShot of Lambda AWS Node](https://i.ibb.co/bXnnkpn/Captura-de-pantalla-2022-02-03-a-las-11-35-40.png)

## Creation of List of Todos

https://96i1fi4mti.execute-api.eu-west-3.amazonaws.com/todos

![ScreenShot of List of Todos](https://i.ibb.co/5jLR4j9/Captura-de-pantalla-2022-02-03-a-las-11-36-48.png)
