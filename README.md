# Welcome to your CDK TypeScript project

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`CriyaServiceCdkStack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template


* `ada credentials update  --provider=conduit --role=IibsAdminAccess-DO-NOT-DELETE --profile=default --account=<<AWS-ACOUNTID>> --once` AWS Credentials
* `cdk bootstrap aws://<<AWS-ACOUNTID>>/us-west-2 aws://<<AWS-ACOUNTID>>/us-east-1 --profile default` CDK Bootstrap