# Deploy Wordpress using CloudFormation

CloudFormation is a great tool for tying together related AWS resources such as instances, DynamoDB tables, IAM users, and more.
In this project deployed the WordPress CMS using a CloudFormation template .
This project provides a CloudFormation template for deploying a fully functional Wordpress site on AWS ,The template includes the necessary resources for a complete deployment, including an Amazon Elastic Compute Cloud (EC2) instance .

## Prerequisites
An AWS account
AWS networking basics
### Deployment Steps
1- start with cloudformationtemplet
![1.png](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\1.png)
2- watched your CloudFormation stack deploy and confirmed that WordPress was deployed on the EC2 instance.
![23333.PNG](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\23333.PNG)
![24.PNG](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\24.PNG)
![11.PNG](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\11.PNG)
3- review the resources managed by the stack:
![26.PNG](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\26.PNG)
The template for deploying Wordpress using CloudFormation typically includes the following resources:
1-An Amazon Elastic Compute Cloud (EC2) instance, which will serve as the web server for the Wordpress site.
2-An Amazon Relational Database Service (RDS) instance, which will store the Wordpress site's data.
3-An Amazon Elastic Block Store (EBS) volume, which will store the Wordpress files.
![27.PNG](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\27.PNG)

#### Cleanup

To delete the stack and all associated resources
![28.PNG](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\28.PNG)
![29.PNG](F:\Mooaz\Courses\MY GIT HUB\Deploy Wordpress using CloudFormation\29.PNG)


#### Conclusion
Deployed  wordpress website via AWS Cloudformation templates

