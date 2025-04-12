# onepageconnect-Application

                          This project aims to develop a serverless contact form for a static website, utilizing AWS cloud services to ensure scalability, security, and operational efficiency. The contact form enables visitors to submit their details and messages, which are securely processed and stored in an Amazon DynamoDB database. The backend is built using AWS Lambda, API Gateway, and DynamoDB, following a serverless architecture that eliminates the need for traditional server management.
The frontend, hosted on Amazon S3, is developed using HTML, CSS, and JavaScript, with form submissions handled asynchronously via the Fetch API. Cross-Origin Resource Sharing (CORS) is implemented to facilitate secure communication between the static website and the API Gateway. The project also incorporates form validation, error handling, and logging using AWS CloudWatch to enhance usability and reliability.

#Modules
•	Frontend: The static website will be hosted on Amazon S3, which includes HTML, CSS, and JavaScript files.
•	Backend: A serverless backend using AWS Lambda and API Gateway. An IAM role assigned to the Lambda function with appropriate permissions to access DynamoDB.
•	Database: Amazon DynamoDB to store form data.
•	Monitoring and logging: CloudWatch for Lambda function logs, API Gateway, and DynamoDB for metrics.


