# Serverless pakcage install
`npm install`

# Build go file
`make build`

# Serverless deploy
`sls deploy` or `sls deploy function -f <Lambda function name>` for specific Lambda function or
`sls deploy -s <stage>` for specific stage

# Serverless build and deploy for dev version with Makefile
`make deploy_dev`

# Run Serverless in Local
`sls offline -s <stage>`
