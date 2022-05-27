1. Install backend app:
packer build -var "environment=backend" packer.json
2. Install batch app:
packer build -var "environment=batch" packer.json
