pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "export AWS_DEFAULT_REGION=ap-south-1"
            sh "aws cloudformation create-stack --stack-name stack18ec2 --template-body file://project-15_Stage1_final04.yml --capabilities CAPABILITY_IAM --region 'ap-south-1'"
              }
             }
            }
            }
