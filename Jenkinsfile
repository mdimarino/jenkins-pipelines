pipeline {
    agent {
        docker {
            image 'hasicorp/terraform:latest'
            args '--entrypoint=""'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'terraform version'
            }
        }
    }
}