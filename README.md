# Serverless API Post
> This repository utilizes AWS Cloud Servers such as API Gateway (Routing), AWS Lambda Functions (CRUD Operation Handlers), and AWS DynamoDB (Database) to accomplish a POST requests.

## Installation

> Start with: `npm install`

## Usage

> To test, use: `npm test`

Get request:
```text
method: POST
route: /cars || /cars/{id}
body: {
  id: NUMBER,
  brand: STRING,
  model: STRING,
  year: NUMBER,
}
```

Output:
> response with status code and body - new car

## UML Diagram
![Serverless API UML Diagram](./public/images/serverless-api.png)

## PR link
[POST Request PR link](https://github.com/cleecoloma/serverless-api-post/pulls)

## Contributors
* Chester Lee Coloma
* ChatGPT helped with the tests