 In this demo, I will be setting up my virtual environment using Terraform. 
 First I will be creating a custom VPC and subnet. 
 Then I will add an Internet Gateway and set up the appropriate route table to connect to the internet.
 After, I will set up the security groups to allow SSH and HTTP/HTTPS then attach an ENI and EIP.
 Last step is to deploy a linux instance and automatically install apache server by using a script in 'user data'.
 
 
 1. Create VPC
 2. Create Internet Gateway
 3. Create Custom Route Table
 4. Create a Subnet
 5. Associate Subnet with Route Table
 6. Create Security Group to allow port 22, 80, 443
 7. Create a network interface with an IP in the subnet that was created in step 4
 8. Assign an elastic IP to the network interface created in step 7
 9. Create linux instance and install/enable apache2
