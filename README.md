## Purpose of this project is to architect an AWS infrastruture for HAH Production environment. 

## Prerequesites
- Design Production VPC
- AWS CLI
- EC2 Kepairs 
- IAM User with appropriate permissions
- AWS Access Key and Secret Key
 
## prod_corp
This file provides CDIR block design for Prod VPC and Corp.

## mysql_RDS
This file provides strategy to migrate local mysql to RDS.

## Config Files

### hah.json
This file provides the configuration for cloudformation to provision HAH Production environment with Multi_AZ, Amazon RDS, Apache web server and PHP, in there existing VPC.

### bootstrap.json
This file contains the configurations to bootstrap helpers to install the Apache Web Server and PHP.
