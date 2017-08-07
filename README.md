This is a hacky modification of the official AWS redshift loader lambda function taken from the zipfile that they provide (version 2.4.7)
It works using the https://github.com/darioatbashton/aws-lambda-local.git lambda wrapper and it has modified to properly use the AWS role based credentials from ec2
