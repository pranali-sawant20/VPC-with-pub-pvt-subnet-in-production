VPC-with-pub-pvt-subnet-in-production
PROJECT ARCHITECTURE:

![image alt](https://github.com/pranali-sawant20/VPC-with-pub-pvt-subnet-in-production/blob/c3ff1ac73a58e51e87475b461d8ffe76ddca183a/architecture.png) 

ABOUT PROJECT:This project demonstrate how to create a vpc that you can use for servers in a production environment.To improve resiliency,deploy the servers in two availability zones,by using
auto scaling group and an application load balancer for additional security, deploying the server in private subnet .the servers receives requests through the load balancer.the servers can 
connect the internet bey using the NAT gateway.To improve resiliency,deploy the NAT gateway in both availability zones.

OVERVIEW:The VPC has public subnets and private subnets in two availability zones.each public subnet contains a NAT gate and a load balanacer node.The servers run in the private subnets are 
launched and terminated by using auto scaling groups and receive traffic from the laod balancer.The server can connecct to the internet by using
the NAT gateway.

OUTPUT:
