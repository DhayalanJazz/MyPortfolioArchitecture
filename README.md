# My Portfolio Architecture
My Portfolio Website Deployed in Amazon Web Services Using Terraform Leveraging Azure Pipelines for Continuous Integration and Deployment.

My Website Link: [Dhayala.com](https://Dhayala.com/)

![Dhayala's Portfolio Architecture.](</Images/Portfolio Architecture.png>)

All the Website static files deployed in S3 Bucket by Azure build when the code is pushed to github from local and CloudFront Caches the website content across the continents set up with a HTTP Request to S3 once a week to fetch the updated and new contents of the website.
All the AWS Services are deployed using Terraform (Infrastructure as Code Tool). Lambda and DynamoDB is integrated with the website to add the viewers count and display it to the user when the website is loaded.
