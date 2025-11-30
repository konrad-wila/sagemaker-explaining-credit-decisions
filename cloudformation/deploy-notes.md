aws cloudformation create-stack --stack-name explaining-credit-decisions --template-body file://cloudformation/template.yaml --parameters file://cloudformation/deployment-parameters.json --capabilities CAPABILITY_NAMED_IAM CAPABILITY_AUTO_EXPAND --role-arn arn:aws:iam::695165643296:role/explaining-ai-credit --region us-east-1

