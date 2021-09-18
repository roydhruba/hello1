pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name stack01ec2 --template-body file://project-15_Stage1_final.yml --region 'ap-south-1'"
              }
             }
            }
            }