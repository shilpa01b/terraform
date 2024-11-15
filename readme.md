### Terraform project that involves setting up a VPC and subnet.

# Prerequisites
   1.[Terraform](https://www.terraform.io/downloads.html) installed on your machine.
   
   2.An AWS account with permissions to create VPCs and associated resources.
   
   3.AWS CLI configured with your credentials.

# terraform AWS VPC and subnet setup
    1.Install Terraform from official terraform website.

    2. For the first time to setup infra in terraform first login into aws console , create IAM user with adminaccesspolicy.

    3.Create provider file with extension .tf which state that where to create infra. Here we use AWS provider
    link --  https://registry.terraform.io/providers/hashicorp/aws/latest
   

    4. Write code to create vpc and subnet.
       

# Directory Structure
    It helps the user to understand where to find files.
    
    1.main.tf              # Main configuration file for VPC and subnets
    2.Provider.tf          # Ptovider used in the terraform configuation.
