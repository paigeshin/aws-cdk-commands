# aws-cdk-commands

```bash

# Install AWS CLI
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo installer -pkg AWSCLIV2.pkg -target /

# Configure AWS CLI 
aws --version 
aws configure 
aws s3 ls # Check if permission is granted by listing s3 buckets

# CDK INITIALIZE & DEPLOY 
cdk --version
cdk init app --language typescript
cdk bootstrap
cdk synth
cdk deploy
cdk deploy {your_stack_name}

# check 
cdk list 

# code differences 
cdk synth
cdk diff 

# destory 
cdk destroy {your_stack_name}

# find problems
cdk doctor

```
