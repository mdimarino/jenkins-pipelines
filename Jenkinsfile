pipeline {
    agent {
        docker { image 'amazon/aws-cli:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'aws --version'
            }
        }
    }
}
