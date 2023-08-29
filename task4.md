1. Imagine you need to make changes to the configuration of an existing AWS EC2 instance that's being managed by Terraform. How might you go about making those changes while minimizing disruption to your production environment?

by making the changes in the new environment and then after making the sure the changes are tested then apply these changes in the e=production environment.
​ 2. In your own words, what is a module in Terraform?

It is away to organise terraform project by seprating the different resources in seprate folders and manage the interaction between them.
​ 3. What are some advantages of using modules in your Terraform code?

Septating concerns

Manage the terraform peoject easily
​ 4. What are some instances that you might use an output block?

Any resources information you would like to get it as output such as Output VPC and load balancer information
​ 5. How can you pass arguments to a module? What steps do you need to take to add an argument?

by using variables in varaiable file and assign their values in \*tfvar file and pass the variable values it the output file.
​ 6. Imagine you're creating a Terraform module to deploy an AWS VPC. What are some variables you might define for this module to make it adaptable for different environments?

cider-block, vpc_id
