# Terraform AWS Project 

##  Overview

This project provisions a complete AWS infrastructure using Terraform. It includes networking, compute, and load balancing components.

### Resources Created:

* VPC
* 2 Public Subnets (Multi-AZ)
* 2 Private Subnets
* Internet Gateway
* Route Tables
* NAT Gateway
* EC2 Instances (Private Subnets)
* Application Load Balancer (ALB)
* Modular Code Structure
* Proper Use of Variables
*  Outputs & Code Clarity 

---

##  Terraform Apply Output

Apply complete! Resources: 0 added, 2 changed, 0 destroyed.

### Outputs:

alb_dns = "my-alb-1044721478.us-east-1.elb.amazonaws.com"

instance_ids = [
"i-03e14d033f3483cfd",
"i-0bfc18f05ddf775dc"
]

public_subnet = [
"subnet-044dd3154a62ef0a7",
"subnet-08b713a4e9701d94a"
]

private_subnet = [
"subnet-0dc9417f8bf29640c",
"subnet-0af7c248505aede10"
]

vpc_id = "vpc-017f6b994e599eca3"

Website Link
http://my-alb-1325577071.us-east-1.elb.amazonaws.com
<img width="1440" height="900" alt="Screenshot 2026-04-29 at 1 42 35 AM" src="https://github.com/user-attachments/assets/adbf0966-f32f-48ec-af55-00638598001d" />
<img width="1439" height="860" alt="Screenshot 2026-04-29 at 1 51 51 AM" src="https://github.com/user-attachments/assets/76d0219a-5e5f-411e-b8db-18f3e41ac4a0" />

