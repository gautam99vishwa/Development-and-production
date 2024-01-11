# Development-and-production
# AWS EC2 Instance Setup

This repository provides documentation on setting up AWS EC2 instances for development and production environments, using specific details for the AMI and instance type.

## Steps to Reproduce

### 1. Create an AWS Account
   - Go to [AWS website](https://aws.amazon.com/).
   - Click on "Create an AWS Account" and follow the instructions to set up your account.

### 2. Access AWS Management Console
   - Log in to the [AWS Management Console](https://aws.amazon.com/console/).

### 3. Navigate to EC2
   - Once logged in, go to the EC2 dashboard.

### 4. Launch EC2 Instances
   - Click on the "Launch Instance" button to create a new EC2 instance.

### 5. Select an Amazon Machine Image (AMI)
   - For this setup, we used the following AMI:
     - Amazon Linux 2023 AMI 2023.3.20240108.0 x86_64 HVM kernel-6.1
     - AMI ID: ami-0005e0cfe09cc9050

### 6. Choose an Instance Type
   - Select the instance type based on your requirements.
   - For this setup, we used:
     - Instance Type: t2.micro

### 7. Configure Instance Details
   - Set the number of instances, network settings, and other configurations.

### 8. Add Storage
   - Specify the storage requirements for your instances.

### 9. Add Tags (Optional)
   - You can add tags to help identify and manage your instances.

### 10. Configure Security Groups
   - Define the security group rules based on your environment.

### 11. Review and Launch
   - Review your configurations and click "Launch."

### 12. Create Key Pair
   - If you don't have an existing key pair, create a new one.

### 13. Launch Instances
   - Click "Launch Instances" to initiate the creation of your instances.

### 14. Access Instances
   - Once the instances are running, use SSH (for Linux) or RDP (for Windows) to connect to them.

## AMI Details
   - **AMI Name:** Amazon Linux 2023 AMI 2023.3.20240108.0 x86_64 HVM kernel-6.1
   - **AMI ID:** ami-0005e0cfe09cc9050

## Instance Type
   - **Instance Type:** t2.micro

## Important Note
   - Managing AWS resources comes with costs. Always be mindful of the resources you deploy and regularly check your AWS billing dashboard.

images-
![image](https://github.com/gautam99vishwa/Development-and-production/assets/103621752/f1876948-ad20-4b01-b321-07ace70c0ac8)

![image](https://github.com/gautam99vishwa/Development-and-production/assets/103621752/74b8253f-5f81-49bc-9541-f8a0b9bb072b)
Statement- The running Two instances are named 
1.  Production
2. Developement


