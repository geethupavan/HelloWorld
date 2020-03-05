# HelloWorld
CloudFormation template to create HelloWorld html page - Geethika

Template includes the following:

High availbility using ALB and Auto Scaling
Stack created on AWS free tier account

ALB URL : http://geeth-Appli-YAAJHDKKU4FK-1950391551.us-east-1.elb.amazonaws.com

I accidentally deleted the already created stack. So, I created the stack again.

Updated ALB URL : http://geeth-Appli-1IE2W3AV0OS0J-1710714471.us-east-1.elb.amazonaws.com

We can use the below commnand to create the stack. But I created this by uploading the template using CloudFormation service.

aws cloudformation  create-stack --stack-name geethika-web --template-url  https://helloworld-cloudformation.s3.amazonaws.com/Hello_World.json --parameters file://parameters.json
--tags Key=Name, Value=Geethika-web --on-failure ROLLBACK --role-arn arn:aws:iam::257736767631:role/XXX

Note : Please find the parameters.json file
