How to use this repository
========
This repository is designed to be used as the core setup for Jenkins stack built using Amazon's CloudFoundation service. This setup could be used with any software development system where Deployment follows the concept of Continuous Integration and Delivery using Jenkins with every commit by DevOps via Github.
I've setup Jenkins server, to be run in AWC EC2 Centos server. Also, I provide a CloudFormation template to set up the VPC with 2 EC2 instances, load balancer with auto scaling group and S3 Bucket.

Follow the steps in the full report to setup Jenkins server and Github.
To run the template, you should do the following:

Clone this repository into your machine using the following commands:

git clone git@github.com:fadwakhalil/template.git
git commit -a -m "First Commit" 
git push origin master
and then Jenkins server will fire and the AWS CloudFormation starts creating the stack.

For introduction and understanding of the Continuous integration concept please watch the following videos:
Please have a look at my short video presentation describing the concept and key features of the technology on http://youtu.be/D7113VqS5co
The Long YouTube video - Step-by-Step walkthrough of the entire project can be found on http://youtu.be/0n0qxCEgco4
You can also access my demo and the setup instructions in the presentation attached. 
