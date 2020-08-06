# Project2-IaaC-Udagram
This project creates a CloudFormation stack and deploys an Apache server in an Auto Scaling group handled by a LoadBalancer

## Getting Started
First create a network stack using the command
```bash
create.bat networkstack network.yml network-parameters.json
```

Once the networkstack's status is changed to CREATE_COMPLETE then create the server stack by running the following command
```bash
create.bat serverstack servers.yml server-parameters.json
```
