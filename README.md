# AWS Serverless Expense Tracker

## Author
**Keona Lollis**

## Project Overview

This project is a serverless expense tracking application built on Amazon Web Services (AWS). The application allows users to add and retrieve expense records through AWS Lambda functions connected to Amazon API Gateway and Amazon DynamoDB. The frontend is a static website hosted on Amazon S3.

## AWS Services Used

- Amazon S3
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- AWS IAM
- Amazon CloudWatch

## Project Structure

```
docs/
    Expense Tracker Assignment.docx

lambda/
    createExpense
    getExpenses

website/
    index.html
    style.css

screenshots/

README.md
```

## Features

- Create new expense records
- Retrieve saved expenses
- Serverless architecture
- Static website hosted on Amazon S3
- REST API using API Gateway
- Data stored in DynamoDB
- CloudWatch logging for monitoring and troubleshooting

## Screenshots

The repository includes screenshots demonstrating:

- Lambda Functions
- API Gateway
- DynamoDB Table
- DynamoDB Items
- S3 Static Website
- Expense Tracker User Interface
- Lambda Test Results

## Technologies

- HTML
- CSS
- JavaScript
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- Amazon S3

## Future Improvements

- User authentication with Amazon Cognito
- Expense categories and filtering
- Monthly expense reports
- Charts and analytics
- Improved responsive design