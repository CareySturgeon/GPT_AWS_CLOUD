# GPT_AWS_CLOUD
GPT/AWS/Cloud/DevOps
GPT's Description: 

This YAML script creates an EC2 instance and an S3 bucket. The EC2 instance is created with an Amazon Linux 2 AMI, a t2.micro instance type, and a security group specified by its ID. The user data section of the EC2 instance is used to install and start Apache web server, and create a simple HTML file.

The S3 bucket is created with the specified name, which must be globally unique across all AWS accounts. You can use this bucket to store images or other files.

You can save this YAML script as a file and use it with the AWS CloudFormation service to create the resources described in the script.
