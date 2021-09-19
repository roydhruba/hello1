pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name stack08ec2 --template-body file://project-15_Stage1_final03.yml --capabilities CAPABILITY_IAM --region 'ap-south-1'"
              }
             }
            }
            }
