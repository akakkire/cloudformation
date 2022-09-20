pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation delete-stack --stack-name takehome-ecs --template-body file://takehome_ecs.yaml --region 'us-east-1'"
            }
        }
    }
}
