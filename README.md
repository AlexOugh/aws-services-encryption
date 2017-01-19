# Lambda Environment Variable Encryptor

Lambda Function to encrypt secret environment variables of Lambda Functions.
This Function is integrated with CodePipeline to encrypt secret values after target Lambda Function is successfully deployed.

Please see this for more details on how to integrate Lambda Functions in CodePipeline,
http://docs.aws.amazon.com/codepipeline/latest/userguide/how-to-lambda-integration.html#how-to-lambda-integration-add-action

![aws-services][aws-services-image]

## How To Setup a CodePipeline

Please see here, https://github.com/SungardAS/aws-services-federation#how-to-setup-a-codepipeline

## How To Test Lambda Functions

- $ cd tests
- Export environment variables, SSO_HOST, SSO_BASIC_AUTH_USERNAME, SSO_BASIC_AUTH_PASSWORD, SSO_MASTER_TOKEN
- Replace \<username\> and \<password\> with proper values in 'test_authorizer.py'
- $ python test_authorizer.py

[aws-services-image]: ./docs/images/logo.png?raw=true
