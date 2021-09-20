pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name stack15ec2 --template-body file://project-15_Stage1_final02.yml --capabilities CAPABILITY_IAM --cfn-role-arn --region 'ap-south-1'"
              }
             }
            }
            }
