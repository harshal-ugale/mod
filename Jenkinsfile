pipeline {
    agent any
	stages {
	    stages {'Clone Repo'} {
		    steps{
			sh"export AWS_DEFAULT_REGION=us-eastr-1"
			sh"aws cloudformation create-stack --stack-name group4 --template-body file://S3Bucket.json --region 'us-east-1'"
			
			}
		}
	}	
}