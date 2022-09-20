pipeline {
    agent any
    stages {
        stage('ECSCluster') {
            steps {
            sh "aws cloudformation create-stack --stack-name takehome-ecs --template-body file://takehome_ecs.yaml --region 'us-east-1'"
            }
        }
    }
}
