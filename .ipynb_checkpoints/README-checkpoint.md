# Well Log File Organizer
A Python package to ensure that we will only process unique well log files in TIFF format.

## Running
1. Create a file `configs/config` by using `configs/config.template` as an example
1. Create an S3 bucket with `bin/bucket.sh create`
1. Create a DynamoDB table with `bin/database.sh create`
1. Deploy AWS Lambda function with `bin/lambda.sh create`
