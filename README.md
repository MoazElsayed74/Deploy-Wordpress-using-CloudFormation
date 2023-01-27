# Deploy Wordpress using CloudFormation

CloudFormation is a great tool for tying together related AWS resources such as instances, DynamoDB tables, IAM users, and more.
In this project deployed the WordPress CMS using a CloudFormation template .
This project provides a CloudFormation template for deploying a fully functional Wordpress site on AWS ,The template includes the necessary resources for a complete deployment, including an Amazon Elastic Compute Cloud (EC2) instance .

## Prerequisites
An AWS account
AWS networking basics
### Deployment Steps
1- start with cloudformationtemplet

<img src="images/1.png">

2- watched your CloudFormation stack deploy and confirmed that WordPress was deployed on the EC2 instance.

<img src="images/23333.png">

<img src="images/24.png">

<img src="images/11.png">

3- review the resources managed by the stack:

<img src="images/26.png">

The template for deploying Wordpress using CloudFormation typically includes the following resources:
1-An Amazon Elastic Compute Cloud (EC2) instance, which will serve as the web server for the Wordpress site.
2-An Amazon Relational Database Service (RDS) instance, which will store the Wordpress site's data.
3-An Amazon Elastic Block Store (EBS) volume, which will store the Wordpress files.

<img src="images/27.png">

#### Cleanup

To delete the stack and all associated resources
<img src="images/28.png">
<img src="images/29.png">


#### Conclusion
Deployed  wordpress website via AWS Cloudformation templates

