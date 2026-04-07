# AWS-Labs
A collection of hands-on labs completed through AWS Skill Builder as part of preparing for the AWS Certified Cloud Practitioner certification. Each lab was completed in a live AWS environment with real services.

Labs Completed
Lab 1 — Introduction to Amazon S3
Goal: Create and configure an S3 bucket, manage object permissions, and enable versioning.
What I did:

Created an S3 bucket (reportbucket-704850761548) in us-east-1
Uploaded an object (new-report.png, 84.0 KB) to the bucket
Managed object-level access permissions — successfully made the object publicly accessible
Created and applied a bucket policy to control access
Enabled bucket versioning to protect against accidental overwrites or deletions

Concepts covered:
Amazon S3 Bucket Creation Object Storage Access Permissions Bucket Policies Versioning Public Access![new report](https://github.com/user-attachments/assets/62770f0a-aa42-4590-9c40-9806d6ec2fa6)

![bucket summary](https://github.com/user-attachments/assets/ccd325e5-9513-483c-bbfb-5af9ae6cc59a)


Lab 2 — Introduction to Amazon VPC
Goal: Create a VPC using the VPC Wizard and explore its core networking components.
What I did:

Created a VPC (Lab-vpc) using the AWS VPC Wizard with IPv4 CIDR 10.0.0.0/16
Configured two subnets within the VPC in eu-west-2a:

Lab-subnet-public1-eu-west-2a — public subnet
Lab-subnet-private1-eu-west-2a — private subnet


Explored route tables (main, private, and public), network ACLs, and internet gateways
Reviewed the VPC resource map showing the full relationship between components

Concepts covered:
Amazon VPC Subnets Route Tables Network ACLs Internet Gateway CIDR Blocks Public vs Private Subnets
![vpc](https://github.com/user-attachments/assets/4ebcafe4-4b8f-4fc8-b722-0f06c3861877)



