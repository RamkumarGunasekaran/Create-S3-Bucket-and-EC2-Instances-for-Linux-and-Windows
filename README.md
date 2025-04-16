 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
       To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
    This experiment aims to demonstrate the creation of an Amazon S3 bucket for storage purposes and the setup of EC2 instances for both Linux and Windows operating systems using AWS. Amazon S3 (Simple Storage Service) provides secure and scalable object storage, while EC2 (Elastic Compute Cloud) allows users to deploy virtual servers for computation and application hosting.

## ALGORITHM
 ### Steps 1:
 ## Login to AWS Management Console:
     1.Open the AWS Management Console.
     2.Navigate to the S3 service for bucket creation and EC2 for instance setup
 ### Steps 2:
 ## Create an S3 Bucket:

     1.Go to the S3 service.
     2.Click on Create bucket.
     3.Provide a unique Bucket Name and select the Region.
     4.Configure additional settings as per requirements and click Create bucket.
 ### Steps 3:
 ## Launch EC2 Instance (Linux):

     1.Go to the EC2 service.
     2.Click Launch Instance.
     3.Select an Amazon Machine Image (AMI), such as Amazon Linux 2.
     4.Choose an Instance Type (e.g., t2.micro).
     5.Configure instance settings, key pair, and security groups, then Launch the instance.
 ### Steps 4:
## Launch EC2 Instance (Windows):

     1.Repeat the EC2 launch steps but select a Windows Server AMI.
     2.Complete instance configuration and Launch.
 ### Steps 5:
## Connect to Instances:

      1.Linux Instance: Use SSH to connect.
```
ssh -i "key_pair.pem" ec2-user@<linux_public_dns>
```
## COMMANDS
S3 Bucket Creation
1.AWS CLI Command:
aws s3 mb s3:// --region
## EC2 Instance (Linux) Commands
Launch Linux EC2 instance and set up SSH access.

## EC2 Instance (Windows) Commands
Launch Windows EC2 instance and connect using RDP.

## OUTPUT
### REG NUMBER: 212223220084
### NAME: RAMKUMAR G
## S3 Buckets:
![433759805-6556aa0b-44db-4375-89f4-ec7e548f8d1b](https://github.com/user-attachments/assets/a3fd9af8-2d40-461a-8e3a-83ce4f826fe0)

![387316081-25559cac-fc7f-4ef6-a1be-16dbc8775267](https://github.com/user-attachments/assets/699b5203-3f7d-4fb3-bfe5-5ce00cdfbe80)

![387316702-1690bd8a-bf80-40a3-94f0-5cb249834f79](https://github.com/user-attachments/assets/da00ed7b-24e2-4140-bebe-c5d430c60b08)

![387316791-68bf1fc0-31da-4fe3-965c-93b5eeede6db](https://github.com/user-attachments/assets/10f49b15-1259-42a9-ac84-ba6db241ad85)


## RESULT
 
Thus ,The experiment to create an S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.
  


