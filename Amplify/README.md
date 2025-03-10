# Serverless Web App Project

Welcome to the Serverless Web App Project! This README provides you with all the information you need to get started with our serverless web application built using AWS Amplify, AWS Lambda, DynamoDB, and API Gateway.

## :rocket: Introduction

Our project allows you to create a serverless web application that calculates the area of a rectangle based on user-provided length and width values. 
## :scroll: Quick Start

Follow these steps to get your serverless web app up and running:

1. **Prerequisites**

   - Have an AWS account.

2. **Creating the Front-end**

   - Use the `index.html` file from the project files or create a new file.
   - Open a text editor and copy the provided HTML and JavaScript code into the `index.html` file.
   - Replace `"YOUR API URL"` with the actual API Gateway URL later.

3. **Hosting the App on AWS Amplify**

   - Access the AWS console and search for "Amplify."
   - Click on "Get Started" and follow the on-screen instructions to configure your app.

4. **Creating a Lambda Function for Calculations**

   - Search for "Lambda" in the AWS console and create a new function.
   - Copy the provided Lambda function code from this README into your `lambda_function.py` file.

5. **Create an API Gateway**

   - Search for "API Gateway" in the AWS services and set up a new REST API.
   - Create a new POST method and link it to your Lambda function.

6. **Setting up a Database on DynamoDB**

   - Create a new DynamoDB table in the AWS console.

7. **Testing**

   - Open your AWS Amplify domain to access your app.
   - Input values for the length and width and click "Calculate" to get the area of the rectangle.

## :page_with_curl: Project Structure

Here are the key files in this project:

- **`index.html`**: The front-end code for your web app.
- **`areaa.py`**: The Python code for the AWS Lambda function.
- **`Dynamo_Role.json`**: The permissions for the Lambda function on DynamoDB
- **`README.md`**: This README file.

## :tada: Conclusion

With the steps outlined above, you can easily create your own serverless web application for calculating the area of a rectangle. Enjoy the simplicity, speed, and cost-effectiveness of AWS Amplify, Lambda, DynamoDB, and API Gateway.
