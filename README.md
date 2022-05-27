1. Install backend app:
packer build -var "environment=backend" -var-file=variables.json packer.json
2. Install batch app:
packer build -var "environment=batch" -var-file=variables.json packer.json
