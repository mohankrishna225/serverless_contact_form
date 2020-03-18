# Serverless_Contact_Form
Serverless Contact Form running on AwsLambda, ApiGateway, SES.
![serverless-contact-form.png](/serverless-contact-form.png)<br>

1.Setup Email Service using Simple Email Service<br>
2.Create a IAM Role for lambda to access SES and Cloudwatch<br>
3.Create a Lambda Function with Iam Role.<br>
4.Add a Trigger with Apigateway to this lambda function.<br>
5.Test if its created successfully or not using <br>
  curl -i your_api_gateway_url --data-urlencode "name=John" --data-urlencode "email=john@example.com" --data-urlencode "message=hi there"<br>
6.Now create a webpage for the UI.<br>
7.And Host this webpage through S3.
 { https://medium.com/@kyle.galbraith/how-to-host-a-website-on-s3-without-getting-lost-in-the-sea-e2b82aa6cd38 }
 
