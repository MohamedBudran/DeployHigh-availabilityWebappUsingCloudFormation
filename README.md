You can run the supporting material in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Check the region in the create.sh file
./create.sh udagramStack udagram.yml udagram.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./update.sh udagramStack udagram.yml udagram.json
```
