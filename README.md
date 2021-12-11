# How to install Terraform on Mac OS
Here is easy 3-step

## Step-1 Create a working directory for Terraform

 sudo mkdir -p /opt/terraform
 
 cd /opt/terraform

## Step-2 Download Terraform installable zip file and unzip for MacOS

 sudo curl -O  https://releases.hashicorp.com/terraform/1.1.0/terraform_1.1.0_darwin_amd64.zip

 sudo unzip terraform_1.1.0_darwin_amd64.zip

## Step-3 Add terraform to PATH

 cd ~
 
 sudo vi ~/.bash_profile
 
 PATH="/opt/terraform:${PATH}"
 
 export PATH
 
 source ~/.bash_profile
 
 
##  Finally, after executing it, make sure terraform version is available... 

 terraform --version
 
 Thanks! This way, we have successfully installed Terraform on Mac OS
