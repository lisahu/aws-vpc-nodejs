# aws-vpc-nodejs
In this project, I set up a nodejs web server system using Terraform and Ansible.

First, I build an AWS Virtual Private Cloud (VPC) using Terraform. see main.tf.
This VPC uses EC2s as nodejs webservers. Besides, it contains subnets, ELB,
Auto-Scaling Group (ASG), Launch Configuration, AMI, S3, securityGroup, ACLs,
and other AWS services.

Second, I configure and deploy nodejs servers using Ansible. see config_deploy.yml
By running the Ansible playbook, nodejs configuration is deployed to remote hosts.
    
