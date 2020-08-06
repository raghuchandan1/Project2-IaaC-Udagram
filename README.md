# Project2-IaaC-Udagram
This project creates a CloudFormation stack and deploys an Apache server in an Auto Scaling group handled by a LoadBalancer

## Getting Started
First create a network stack using the command
```
create.bat <stack-name> network.yml network-parameters.json
```

Then create the server stack by running the following command
```
create.bat <stack-name> servers.yml server-parameters.json
```
