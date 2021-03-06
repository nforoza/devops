# Deploy a high-availabilty web app using CloudFormation

### Pre Requisites
- Open an AWS Account
- Install AWS Cli https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html

### Remember to configure your aws account with a key
`aws configure`
 
## Deployment Diagram

![Deployment Diagram](Diagram.PNG)

## Deployment using script for Windows  

#### Deploy network infrastructure
`.\create.bat nahuel-udagram-network nahuel-udagram-network.yml nahuel-udagram-network-parameters.json --region=us-west-2`

#### Deploy servers  
`.\create.bat nahuel-udagram-servers nahuel-udagram-servers.yml nahuel-udagram-server-parameters.json --region=us-west-2`

## License

MIT License

Copyright (c) 2020 Nahuel Oroza

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
