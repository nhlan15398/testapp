1. Install backend app:
packer build -var "timestap=backend" -var-file=variables.json packer.json
2. Install batch app:
packer build -var "timestap=batch" -var-file=variables.json packer.json
