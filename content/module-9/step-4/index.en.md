---
title: 'Clean up'
weight: 113
---

### CDK project clean up

When you're done trying out your API Gateway, you can tear down both the state machine and the API Gateway using the AWS CDK. Issue `cdk destroy` in your app's main directory.

wait till you see a success message as shown in the diagram below.
![CDK Destroy](/static/img/module-9/cdk-destroy.png)

### Cloud9 clean up

Select the `stepfunctionsworkshop` Cloud9 environment and then click on Delete. Confirm by typing `Delete` in the text box provided.

### IAM Role clean up

- Go to IAM console
- select (or search for) the role - **stepfunctionsworkshop-admin**
- Click Delete