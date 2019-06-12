## aws-cloudformation-EC2-with-RDS

### Description:

#### steps:
1. EC2WithRds.yaml

### dynamoDB Stack:
~~~
Upload dynamodb.yaml Stack.
~~~

**Description:**
This stack create dynamoDB table with name 'customers' and create IAM role with LambdaFullAccess and apiGatewayFullAccess.




### Tips:
#### 1.
use this in to post method in apiGateway
~~~
{ "customersId":"Any Number","Name":"Any value","Location":"Any location" }
~~~
