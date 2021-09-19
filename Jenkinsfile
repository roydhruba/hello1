pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name stack02ec2 --template-body file://project-15_Stage1_final03.yml --region 'ap-south-1'"
              }
             }
            }
            }
