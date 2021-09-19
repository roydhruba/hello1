pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name stack03ec2 --template-body file://project-15_Stage1_final02.yml --region 'ap-south-1'"
              }
             }
            }
            }
