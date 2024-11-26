# Terraform AWS instances

## Inputs:

* ami_id(opitional) : ami_id opitional default value
* security_group_ids (opitional): list of security group ids. default is  dedault is
* instance_type(opitional): Default value is t3.micro.
* tags(opitional): Default value is empty

## outputs

* public_ip:  outputs the public IP od the instance created.
* private_ip:  outputs the private IP od the instance created.
* instance_id:  outputs the instance created.