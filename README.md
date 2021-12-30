# sam-step-function-api-gateway
APi Gateway invokes the Step function and based on the state machine flow given in the demo-step-functions\statemachine\validator.asl.json

Test API Gateway from Postman by passing the message from BODY
Select POST method and take the URL from API Gateway Staging and add resource name at the end

https://XXXXX.amazonaws.com/dev/validate

{
    Price: "100.00",
    Availability: "Yes"
 }
