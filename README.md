# Serverless Web Application on AWS

## Project Name: Serverless Web Application on AWS

### Deployed at: 
https://greeting.aws-webapp-pranav.click/

### Project Description:

A serverless web application built on AWS that displays the number of views each time the page is refreshed. This project leverages AWS services such as S3, Lambda, DynamoDB, Route 53, and CloudFront to ensure scalability, reliability, and low latency.

### Project Architecture:

![Serverless Web Application on AWS Architecture](https://user-images.githubusercontent.com/66474973/228492073-5cd3d975-3439-4ce4-b109-fb33997df3c3.png)

### Deployment Overview

1. Clone the Repository:

&ensp; ```git clone https://github.com/pranavr753/serverless-aws```

2. Setup AWS Services:

* S3: Create a bucket and upload frontend files.
* CloudFront: Configure distribution to serve S3 content.
* DynamoDB: Create a table to store view counts.
* Lambda: Deploy the provided Lambda function.
* Route 53: (Optional) Configure your custom domain.

3. Configure Frontend:

Update the JavaScript fetch URL to point to your deployed Lambda endpoint.

Visit your CloudFront URL or custom domain to see the view counter in action.

### Components:

* Amazon S3: Hosts the static frontend files (HTML, CSS, JavaScript).
* AWS Lambda: Handles backend logic to increment and retrieve view counts.
* Amazon DynamoDB: Stores the view count data.
* Amazon CloudFront: Distributes the frontend content globally with low latency.
* Amazon Route 53: Manages DNS and custom domain configurations.

### Technologies Used

* Frontend: HTML, CSS, JavaScript
* Backend: AWS Lambda (Python)
* Database: Amazon DynamoDB
* Hosting: Amazon S3
* CDN: Amazon CloudFront
* DNS Management: Amazon Route 53


### Steps to Build the Project:

* View Counter: Displays the number of times the page has been viewed.
* Serverless Backend: Utilizes AWS Lambda and DynamoDB for efficient backend operations.
* Global Content Delivery: CloudFront ensures fast loading times worldwide.
* Custom Domain Support: Easily set up with Route 53 for a personalized URL.

### Outcomes:

Upon completing the project, I learnt how we can have a running serverless web application hosted on AWS. \
Got experience building a serverless application using AWS Lambda, DynamoDB, S3, CloudFront. \
Additionally, I also learnt working with AWS services and integrating them to build a complete solution.

Using this project I wanted to improve my skills in cloud computing, serverless architecture, and AWS services.

Link to the documentation: https://docs.google.com/document/d/1vXYHyx-MiUOAzEF_Vr3DwED4LqmO3BwEEUOdcdnpQn4/edit?usp=sharing. 

### Contact:

Feel free to customize this README further to better fit your project's specifics and personal preferences. Adding a screenshot of your application in action can also enhance the visual appeal and understanding for potential users and contributors.

If you need any more assistance or specific sections added, please reach out to me at pranavr753@gmail.com!
