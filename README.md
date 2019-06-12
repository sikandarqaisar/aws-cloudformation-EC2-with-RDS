## AWS-CloudFormation-EC2-with-RDS


<img src= "https://github.com/sikandarqaisar/CloudFormation-MYSQLWebApplication/blob/master/template.jpg" width="600" height="600">







### Description:
EC2 instance connect with RDS and RDS read Replica and Read Replica have Elastic Cache (Redis).


### Upload Stack:
~~~
Upload EC2&Rds.yaml File.
~~~

**Description:**
Upload this file in aws-cloudformation. Stack Created by this file will Create two EC2 Instances with Ubuntu AMI, and Relation Database Service (RDS) with their Read Replica and MultiAZ unable. Both Instances are in different Availability Zone. First Instance is connected to main RDS Instance and second one is connected to Read Replica of that RDS Instance just for Read operation from database. Then this stack create Redis Elastic Cache and attach it to the Second Instance that have Read Only access to the data base. Simple Database Web Application is already on S3 bucket that have publically accessable.    




### Tips:
#### 1.
~~~
Use Public IPs of EC2 Instances to test data. 
~~~
