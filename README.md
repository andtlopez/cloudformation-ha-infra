# cloudformation-ha-infra
AWS CloudFormation repository that creates the network and the services for a HA infrastructure
Usage:
1. Create network using create-network.sh (pass a stack name, network.yml, and network-params.json) 
2. Sample: "./create-network.sh webapp-network network.yml network-params.json"
3. Check CloudFormation on AWS Console and see if stack's status is "CREATE_COMPLETE"
4. Create services using create-services.sh (pass a stack name, services.yml, and services-params.json)
5. Sample: "./create-services.sh webapp-services services.yml services-params.json"
