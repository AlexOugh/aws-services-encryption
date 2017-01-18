
# Lambda Environment Variable Encryptor

Lambda Function to encrypt secret environment variables of Lambda Functions.
This Function is integrated with CodePipeline to encrypt secret values after target Lambda Function is successfully deployed.

Please see this for more details on how to integrate Lambda Functions in CodePipeline,
http://docs.aws.amazon.com/codepipeline/latest/userguide/how-to-lambda-integration.html#how-to-lambda-integration-add-action


![aws-services][aws-services-image]

## How To Setup

    $ AWS CodePipeline, 'aws-services-encryption'


## How To Test Lambda Functions

    $ cd tests
    $ python test.py

[aws-services-image]: ./docs/images/logo.png?raw=true
