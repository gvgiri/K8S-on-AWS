# Following are the steps I followed to install AWS CDK on Ubuntu
## Install AWS Cli -- follow the steps given in this document
https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html

## check and install latest version of Python

## Install AWS CDK
### Check the pre-reqs given in https://docs.aws.amazon.com/cdk/latest/guide/getting_started.html
#### Install Node.js -- followed https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04
<details><summary>show</summary>
<p>
```bash
sudo apt update
sudo apt install nodejs
nodejs -v
# Install npm #
sudo apt install npm
aws confgure --profile vgiri
# Install PIP and Virtualenv
  sudo python3 -m pip install --user virtualenv
  
```
</p>
</details>

# Heading
<details><summary>show</summary>
<p>

```bash

#Solution here.....
#Install python > 3.6
brew install python
python3 --version

#Install node from the node.js website
https://nodejs.org/en/download/
node --version

#Install aws-cdk
npm install -g aws-cdk

#Check version installed
cdk --version

https://github.com/aws-samples/aws-cdk-examples
```
</p>
</details>

