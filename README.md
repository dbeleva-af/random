RANDOM

This folders contains files for testing the behavior of terraform random provider. 

SOURCE - Terraform Registry.

DESCRIPTION

Random_provider is not like the other known providers like aws_provider or other. Random_provider is logical provider whose purpose is to bring random (unique) values for resources when it is required. This kind of provider works with terraform logic and is not part of any official provider like AWS, Azure or other. It is very important to describe the difference between the random_pet and random_id witch are doing similarly the same thing and are part of the random_provider. Random_id is producing unique id - a random string and you can choose the length. The random_pet resource produces random string containing several words. 

REQUIREMENTS

1. Terraform installed
2. Account in selected cloud provider - here the verndor I use is AWS.

TESTING

Commands for testing the code:
    terraform init
    terraform validate
    terraform plan
    terraform apply 
    terraform destroy
