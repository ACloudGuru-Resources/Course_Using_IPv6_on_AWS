# Rapidly Deploying IPv6 on AWS

These scripts are used in the “Rapidly Deploying IPv6 on AWS” ACloud.Guru Class.

## Chapter3:

These two CloudFormation Templates (CFTs) are used in Chapter 3 to build IPv4-Only VPCs.

ipv4-mgmt-vpc.template = Launches an IPv4-only Management VPC

ipv4-app-vpc.template = Launches an IPv4-only Application VPC

These are used in the early chapter of this class to quickly build up the IPv4-only management and application VPCs, which we use as a base for manual configuration of IPv6.

These are based on the AWS QuickStart Templates.
https://aws.amazon.com/quickstart/architecture/compliance-nist/

## Chapter4:

index.php file is used to show the client IP address contacting our web server EC2 instance.

CloudWatchLogsIAMPolicy.json is used when configuring VPC Flow Logs.

Windows_netsh_and_PowerShell_IPv6_Commands.txt is a list of IPv6 netsh and PowerShell commands.

webserver2-index.html is the index.html file that is used in the Windows Web Server 2.

## Chapter 5:

Modify_Apache_Logging.txt contains the steps to modify the Apache logging to show the X-Forwarded-For Header.

Malicious_URLs.txt contains some sample malformed URLs that you can try to test your WAF security policies.

## Chapter 6:

We use an S3 bucket policy to restrict access based on the source IPv6 address.

s3-bucket-policy.json is a sample of this type of IAM policy used with an S3 bucket.

## Chapter 7:

Then we have two different methods of IPv6 CloudFormation Templates (CFTs) for the automation chapter.

dual-app-vpc-method1.template

dual-app-vpc-method2.template

Then we have a comparable AWS CLI script for rapid IPv6 deployment.

Useful_AWS_CLI_Commands.txt is a list of the useful IPv6 AWS CLI commands and links to each of their documentation pages.

awscli-ipv6.sh is a bash script that runs AWS CLI commands to quickly deploy an equivalent VPC named NewIPv6VPC.
