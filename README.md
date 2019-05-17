# lambda-copy-oneS3-two-otherS3

Note: S3 Bucket names are unique

This will create two buckets 'lambdas3cp-abv-source' and 'lambdas3cp-abv-target' 
An IAM-Role with CloudWatch and Lambda access
A Lambda function to copy from lambdas3cp-abv-source' to 'lambdas3cp-abv-target' whenever an object is inserted to the 'lambdas3cp-abv-target'
