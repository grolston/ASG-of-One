# ASG of One

CloudFormation template for a simple autoscale group of one. The template allows for a bootstrap URL which is a simple pipe to sh. By providing a bash script that is stored in a github/gitlab raw url which is public accessible, you can bootstrap your ec2 instances in the ASG of One.

## Deploy as CloudFormation

The deployment process leverages AWS CloudFormation and is relatively simple once prerequisites are satisfied. Overall the process entails three steps

**Steps to Deploy:**

1. Open your web browser and login to your AWS Account.
2. Click the `Launch Stack` button below to launch stack.
3. Fill in the parameter values

> **Note:** If you want to open the link as a new tab use `ctrl+click` when clicking the *launch Stack* button below.

[![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=asg&templateURL=https://rolston-cloud-library.s3-us-west-2.amazonaws.com/asg/asg.yml)
