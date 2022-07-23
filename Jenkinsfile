pipeline {
    agent {
        docker {
            image 'hashicorp/terraform:latest'
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