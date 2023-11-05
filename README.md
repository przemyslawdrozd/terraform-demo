# Terraform AWS Infrastructure README
This README provides an overview of the Terraform project responsible for provisioning and managing AWS resources using the AWS provider. The infrastructure created includes the following AWS resources:

# Diagram
![terraform-diagram](https://github.com/przemyslawdrozd/terraform-demo/assets/31375100/474f5f88-be62-48ed-9bed-5a82709b962c)

## terraform list
1. aws_vpc.my-vpc: Virtual Private Cloud.
2. aws_internet_gateway.my-gw: Internet Gateway.
3. aws_route_table.my-route-table: Route table.
4. aws_network_interface.web-server-nic: Network interface for the EC2 instance.
6. aws_security_group.allow_web: Security group for the web server.
7. aws_instance.my-server: EC2 instance.
8. aws_eip.my-eip: Elastic IP for an EC2 instance.
9. aws_route_table_association.my-rt-asso: Association between a subnet and a route table.
