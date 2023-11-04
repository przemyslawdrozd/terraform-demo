# Terraform AWS Infrastructure README
This README provides an overview of the Terraform project responsible for provisioning and managing AWS resources using the AWS provider. The infrastructure created includes the following AWS resources:

# Diagram

## terraform list
1. aws_eip.my-eip: Elastic IP for an EC2 instance.
2. aws_instance.my-server: EC2 instance.
3. aws_internet_gateway.my-gw: Internet Gateway.
4. aws_network_interface.web-server-nic: Network interface for the EC2 instance.
5. aws_route_table.my-route-table: Route table.
6. aws_route_table_association.my-rt-asso: Association between a subnet and a route table.
7. aws_security_group.allow_web: Security group for the web server.
8. aws_subnet.my-subnet: Subnet within the VPC.
9. aws_vpc.my-vpc: Virtual Private Cloud.