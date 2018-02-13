## Purpose of this project is to architect an AWS infrastruture for HotelsAtHome Production environment. 

## Prerequesites
- Design Production VPC
- AWS CLI
- EC2 Kepairs 
- IAM User with appropriate permissions
- AWS Access Key and Secret Key
 
## VPC_Prod
This file provides CDIR block design for Production VPC 

## Config Files

### hah.json
This file provides the configuration for cloudformation to provision Hotels At Home Production environment with Multi_AZ, Amazon RDS, Apache web server and PHP, in there existing VPC.


### bootstrap.json
This file contains the configurations to bootstrap helpers to install the Apache Web Server and PHP.