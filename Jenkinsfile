pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name takehome-ecs2 --template-body file://takehome_ecs.yaml --region 'us-east-1'"
            }
        }
    }
}
