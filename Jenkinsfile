pipeline {
    agent {
        docker { 
            image 'amazon/aws-cli:latest'
            args '--entrypoint=""'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'aws --version'
            }
        }
    }
}
