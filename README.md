# How to Upload Any Type of Binary File to S3 via API Gateway

## Upload any type of file to the S3 bucket using Lambda proxy integration with API Gateway in Python


### Prerequisite
- AWS Serverless Application Model(SAM) must be installed on your machine

**Follow the below steps to deploy this small module to AWS Cloud** 

1. Clone this repo.
2. Run `sam build`.
3. Run `sam deploy --guided`. 
4. Enter details as asked in CLI.

**Note:** Write unique name of your bucket
  * The following rules apply for naming buckets in Amazon S3
      - Bucket names must be between 3 and 63 characters long.
      - Bucket names can consist only of lowercase letters, numbers, dots (.), and hyphens (-). 
      - Bucket names must begin and end with a letter or number.
      - Bucket names must not be formatted as an IP address (for example, 192.168.5.4). 
      - Bucket names must not start with the prefix `xn--`.

**Follow the below steps to remove this small module from AWS Cloud** 

1. First, empty your s3 bucket from console.
2. Go to the inside of your project folder on your machine.

And run the below command.
```
aws cloudformation delete-stack --stack-name <stack-name> --region <region>
```
