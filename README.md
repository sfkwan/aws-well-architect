Please draw the AWS diagram follow aws well architecture.
Use in AWS HK. With public and private subnet and use of multiple AZ and global NAT gateway. Use of the corresponding VPC gateway/ interface endpoint to access securely access corrsponding AWS resources.

I am going to use ECS over fargate and my task will access, RDS, s3 and ECR and send log and metric to cloudwatch. API will be exposed via api gateway with WAF enabled. I will also integrate AWS cognito.

Ship transaction data from RDS to S3 table DMS and then set up data catalog using glue and Redshift spectrum for analytic.