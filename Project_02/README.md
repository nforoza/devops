# Deploy a high-availabilty web app using CloudFormation

### Pre Requisites
AWS Cli https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html
An AWS Account

### Remember to configure your aws account with a key
aws configure

## Example
### Deploy network infrastructure
.\create.bat nahuel-udagram-network nahuel-udagram-network.yml nahuel-udagram-network-parameters.json --region=us-west-2

### Deploy servers from Windows 
.\create.bat nahuel-udagram-servers nahuel-udagram-servers.yml nahuel-udagram-server-parameters.json --region=us-west-2
