# AWS-Email-Marketing-App
![image](https://github.com/user-attachments/assets/3583278d-169e-4d30-b1b5-47411a0d3520)

Testing of Newsletter Function
![Screenshot 2024-09-11 153203](https://github.com/user-attachments/assets/2b1fa3be-6ec1-43de-badc-a12e2f5ac378)

Amazon S3: Stores content like email templates, csv of subscriber list
AWS Lambda: Executes the code in response to the events, and process the newsletter content
Amazon EventBridge: Which triggers lambda functions based on scheduled events (scheduling an email sent to list of subscribers at a timing stated, can be recurring)
SES (Simple Email Service): Sends the actual email newsletters to your subscribers using the processed content.
These tools help automate the flow from content creation to delivery

Mail Project using AWS
What you need
-Email Addresses to send to that you can validate
-An Email address to send from that you can validate
-Basic Knowledge of AWS
-A Text editor or somewhere to write HTML code 

High Level Requirements
-place to store email templates and list of contacts
-A way to send emails
-a Way to merge email templates with contacts and send them to email service
-a way to trigger sending of emails on a schedule
-Cleanup at the end
