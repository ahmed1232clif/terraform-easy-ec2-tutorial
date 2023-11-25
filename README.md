# terraform-easy-ec2-tutorial
launching a ec2 instance with terraform - basic task 
Before starting with terraform you need to have aws cli installed and setup in your pc 
then you need to have the IAM user with access keys 
then we can start with terraform

First go to terraform download https://developer.hashicorp.com/terraform/install?product_intent=terraform 
after downloading unzip the file and store it in c:\ drive (Recommended) and copy the path 
then go to environment variables and edit the PATH and add NEW path paste the path ending with "\" and verify it by running a command 
on cmd "terraform --version"

Now you can create a folder and open with the IDE for example VScode 
new terminal and run the command "aws configure" and give the credentials 
after this you can now create a file with an extension .tf for example main.tf 

here refer the code above or you can pull this tf file 

the code can be modified as per your requirements like tags and names and instance type and all 

after saving it 

run these command 

terraform init 
terraform apply

here are more commands you can use before applying the changes 

terraform fmt - which will correct the wrong formats like spaces
terraform validate - which will  validate the code if it is right or there are errors 
terraform plan - which will show the description what will happen after apply 
