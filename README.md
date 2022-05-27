1. Edit varibales:
 -  "vpc-id":""
 -  "subnet-id":""
 -  "security_group_id":""
 to suit the environment on AWS.
2. Install backend app:
packer build -var "environment=backend" packer.json
3. Install batch app:
packer build -var "environment=batch" packer.json
