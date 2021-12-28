# Overview of project

 - Created VPC with 3 public and 3 private subnet with ING and NGW
 - Created SSH key par for autoscaling
 - Autoscaling will lunche  EC2 into private subnet
 - Also, have defined userdata which will install nginx and homepage will print hostname
 - Created s3 Bucket 
 - Created AWS IAM role with s3 GetObject and PutObject policy and have attached to Launch Configuration
 - Created Load balancer with target group


 # Instruction to run terraform scipt 

 - Please configure AWS CLI in your terraform machine
 - I have used us-west-2 region 
 - clone code from :
 - run `terraform plan` to validate 
 - run `terraform apply`

 # ---------------------------------------------------------------------------------------- #





 ****
# Prerequisites:
 
 1.  AWS account 
 2.  IAM role with necessary permissions
 3.  Terraform & AWS CLI configured on machine from which the scripts are to be run