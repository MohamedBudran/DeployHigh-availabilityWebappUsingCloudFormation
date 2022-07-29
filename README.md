url: http://udagr-webap-1k3dy2d6g8mfp-1250230823.us-east-1.elb.amazonaws.com/


![DIAGRAM udagram udacity mohamed budran](https://user-images.githubusercontent.com/83536630/181767454-ee18e0a4-7347-4170-a8fd-288cf3eff710.jpeg)

You can run :
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Check the region in the create.sh file
./create.sh udagramStack udagram.yml udagram.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./update.sh udagramStack udagram.yml udagram.json
```
