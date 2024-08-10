# AWS_Lambda
AWS Definition of Lambda:
Lambda is a compute service that lets you run code without provisioning or managing servers. Lambda runs your code on a highavailability compute infrastructure and performs all of the administration of the compute resources, including server and operating system 
maintenance, capacity provisioning and automatic scaling, and logging.

Key Features of Lambda

• Compute Service
• Highly Available
• All of the administration of the compute resources, including server and operating system maintenance, automatic scaling, and logging.
• Provisioning done by AWS and Pay as you use
• Bring your code and run on Lambda
• Lambda is a serverless, event-driven compute service

Use Case for AWS Lambda

• Event Driven
• Unpredictable demand

AWS Lambda Execution Role

• A Lambda function's execution role is an AWS Identity and Access Management (IAM) role that grants the function 
permission to access AWS services and resources. 
• Default Lambda Function Role Permissions :
• AWSLambdaBasicExecutionRole : AWSLambdaBasicExecutionRole grants permissions to upload logs to CloudWatch.
• Need to provide an execution role when a function is created. Invoke your function, Lambda automatically provides your 
function with temporary credentials by assuming this role.

