# CloudformationTemplates
Includes basic cloudformation templates, i am writing as a part of learning.

## Creating stack via AWS Cli
'aws cloudformation create-stack --stack-name <stackName> --template-body file://<templateFile> --parameters ParameterKey=<Key> ParameterValue=<SomeValue>'
## Updating stack via AWS Cli
'aws cloudformation update-stack --stack-name <stackName> --template-body file://<templateFile> --parameters ParameterKey=<Key> ParameterValue=<SomeValue>'
