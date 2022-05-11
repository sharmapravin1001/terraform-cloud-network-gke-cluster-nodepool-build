
Simply clone this repository and create the GCP terraform cluster along with nodepool. It will automatically create the service account, enable the required api and create VPC and subnet.  



-------------
At the minimal change, you may need to add/change before use this repo.
------------



[1]  Change the subnet_ip_cidr_range in variable.tf if you would like to change it.

[2] It is important to provide your project_id in variable.tf file. 

