Here are the changes you will need to make in your Terraform Files; in the variable.tf file.

You will need to have and enter your own domain name. 

My domain name in this example is devops1.link.

You also will need to enter your own subnet name which you can find under your VPC section in AWS

Under the main rancher.tf file you will need to make these changes

On line 56 enter your VPC ID from your AWS account

On line 84 enter your subnet id's for your load balancer. I have 3 options for mine.

On lines 187 and 190 enter your download path so the pem key can be created and downloaded accordingly
